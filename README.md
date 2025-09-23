# MiniTorch Module 1

<img src="https://minitorch.github.io/minitorch.svg" width="50%">

* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module1/module1/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py tests/test_module.py tests/test_operators.py project/run_manual.py

Task 1.5

"Xor"
<img width="271" height="606" alt="image" src="https://github.com/user-attachments/assets/359d8496-a295-4dcd-9320-b3fa1935cec4" />

PTS = 100
HIDDEN = 6
RATE = 0.5
    
Epoch  10  loss  67.3936327780722 correct 66
Epoch  20  loss  64.36709677327104 correct 74
Epoch  30  loss  61.51011757214012 correct 73
Epoch  40  loss  58.35523819351799 correct 69
Epoch  50  loss  54.78103569834242 correct 75
Epoch  60  loss  50.65262015516789 correct 79
Epoch  70  loss  46.520207946486366 correct 82
Epoch  80  loss  43.140801198739645 correct 84
Epoch  90  loss  39.09887666461215 correct 85
Epoch  100  loss  41.43062214971058 correct 82
Epoch  110  loss  39.88015281741086 correct 82
Epoch  120  loss  35.256056908702405 correct 83
Epoch  130  loss  31.064388260695395 correct 88
Epoch  140  loss  35.50509634803451 correct 80
Epoch  150  loss  28.6103466793356 correct 87
Epoch  160  loss  26.11254110297972 correct 89
Epoch  170  loss  24.727265729625657 correct 89
Epoch  180  loss  22.558230564530525 correct 91
Epoch  190  loss  21.376058565789872 correct 90
Epoch  200  loss  19.262113187464667 correct 93
Epoch  210  loss  18.00451273387337 correct 92
Epoch  220  loss  16.367931340418593 correct 94
Epoch  230  loss  36.213876286090354 correct 82
Epoch  240  loss  14.727332017911156 correct 98
Epoch  250  loss  13.83741394775629 correct 97
Epoch  260  loss  17.70397942162863 correct 89
Epoch  270  loss  15.694708683363054 correct 90
Epoch  280  loss  17.916048210122405 correct 89
Epoch  290  loss  19.537188197167016 correct 89
Epoch  300  loss  14.744169612306576 correct 92
Epoch  310  loss  10.871672101755859 correct 96
Epoch  320  loss  14.268902615016104 correct 91
Epoch  330  loss  14.7965160642194 correct 92
Epoch  340  loss  10.523136533238402 correct 97
Epoch  350  loss  11.31032375171813 correct 95
Epoch  360  loss  14.845868634442956 correct 92
Epoch  370  loss  12.847363506034874 correct 92
Epoch  380  loss  13.896867934752946 correct 92
Epoch  390  loss  9.480430130887344 correct 97
Epoch  400  loss  8.799557313228279 correct 97



"Diag"
<img width="293" height="722" alt="image" src="https://github.com/user-attachments/assets/2412262d-3c1f-4383-ae9b-64c50a3957bf" />


PTS = 50
HIDDEN = 2
RATE = 0.5

Epoch  10  loss  22.1982746989271 correct 42
Epoch  20  loss  19.81580203884386 correct 42
Epoch  30  loss  17.71421374040739 correct 42
Epoch  40  loss  14.89973441460215 correct 42
Epoch  50  loss  11.812400146437165 correct 48
Epoch  60  loss  9.407467598980961 correct 50
Epoch  70  loss  7.669401132878688 correct 50
Epoch  80  loss  6.348321220179678 correct 50
Epoch  90  loss  5.34796690433099 correct 50
Epoch  100  loss  4.573363643687257 correct 50
Epoch  110  loss  3.969228198687205 correct 50
Epoch  120  loss  3.5029142902700605 correct 50
Epoch  130  loss  3.134782331094413 correct 50
Epoch  140  loss  2.83699156753347 correct 50
Epoch  150  loss  2.5886722386800662 correct 50
Epoch  160  loss  2.385702810326714 correct 50
Epoch  170  loss  2.211833588087469 correct 50
Epoch  180  loss  2.0612358615512756 correct 50
Epoch  190  loss  1.931819772436081 correct 50
Epoch  200  loss  1.817047739628355 correct 50
Epoch  210  loss  1.7129236895641857 correct 50
Epoch  220  loss  1.6176841852993245 correct 50
Epoch  230  loss  1.5301108889095927 correct 50
Epoch  240  loss  1.4493019109003173 correct 50
Epoch  250  loss  1.3745486842608723 correct 50
Epoch  260  loss  1.3052678103668602 correct 50
Epoch  270  loss  1.2409622043093298 correct 50
Epoch  280  loss  1.1811981324841094 correct 50
Epoch  290  loss  1.1255910330033727 correct 50
Epoch  300  loss  1.0737963000476576 correct 50
Epoch  310  loss  1.0255029528421098 correct 50
Epoch  320  loss  0.9804290383047775 correct 50
Epoch  330  loss  0.9383181170088334 correct 50
Epoch  340  loss  0.8989364557199238 correct 50
Epoch  350  loss  0.8620707020482263 correct 50
Epoch  360  loss  0.8275259034205639 correct 50
Epoch  370  loss  0.7951237831657555 correct 50
Epoch  380  loss  0.7647012168138252 correct 50
Epoch  390  loss  0.736108870315574 correct 50
Epoch  400  loss  0.7092099735574695 correct 50
Epoch  410  loss  0.6838792099959653 correct 50
Epoch  420  loss  0.6600017080636882 correct 50
Epoch  430  loss  0.6374721231755243 correct 50
Epoch  440  loss  0.616193801285646 correct 50
Epoch  450  loss  0.596078016397223 correct 50
Epoch  460  loss  0.5770432754472382 correct 50
Epoch  470  loss  0.5590146847356733 correct 50
Epoch  480  loss  0.5419233726410633 correct 50
Epoch  490  loss  0.5257059638266617 correct 50
Epoch  500  loss  0.510304100532599 correct 50



"Simple"

<img width="243" height="721" alt="image" src="https://github.com/user-attachments/assets/65c896af-2694-4bff-b557-d61bbdf280a7" />

PTS = 50
HIDDEN = 2
RATE = 0.1

Epoch  10  loss  31.155119702794916 correct 32
Epoch  20  loss  29.661327929710254 correct 40
Epoch  30  loss  28.44100205282098 correct 39
Epoch  40  loss  27.150793001911996 correct 39
Epoch  50  loss  25.7206252607441 correct 40
Epoch  60  loss  24.243031061863206 correct 41
Epoch  70  loss  22.77575881723788 correct 41
Epoch  80  loss  21.392806989312255 correct 41
Epoch  90  loss  20.115699504427006 correct 41
Epoch  100  loss  18.93496677918047 correct 41
Epoch  110  loss  17.850134983477094 correct 41
Epoch  120  loss  16.85624483985975 correct 42
Epoch  130  loss  15.930707659559753 correct 42
Epoch  140  loss  15.056865272054758 correct 43
Epoch  150  loss  14.22629249876733 correct 45
Epoch  160  loss  13.456662399437008 correct 45
Epoch  170  loss  12.73481473974969 correct 46
Epoch  180  loss  12.034678693011672 correct 46
Epoch  190  loss  11.357584122005026 correct 46
Epoch  200  loss  10.710062079783226 correct 46
Epoch  210  loss  10.097367847469922 correct 46
Epoch  220  loss  9.522222527197965 correct 47
Epoch  230  loss  8.9839343182808 correct 47
Epoch  240  loss  8.485823507227204 correct 47
Epoch  250  loss  8.041006776881659 correct 50
Epoch  260  loss  7.62995861354432 correct 50
Epoch  270  loss  7.2451892113755445 correct 50
Epoch  280  loss  6.88631519666689 correct 50
Epoch  290  loss  6.551772766844945 correct 50
Epoch  300  loss  6.240081877495999 correct 50
Epoch  310  loss  5.949690038602024 correct 50
Epoch  320  loss  5.679028984869413 correct 50
Epoch  330  loss  5.426578553462049 correct 50
Epoch  340  loss  5.190913729213188 correct 50
Epoch  350  loss  4.970687921371489 correct 50
Epoch  360  loss  4.764725152220708 correct 50
Epoch  370  loss  4.57134764878761 correct 50
Epoch  380  loss  4.390526598836701 correct 50
Epoch  390  loss  4.22082491130841 correct 50
Epoch  400  loss  4.061409594255383 correct 50
Epoch  410  loss  3.9111267921835733 correct 50
Epoch  420  loss  3.769995876664113 correct 50
Epoch  430  loss  3.6369462262699055 correct 50
Epoch  440  loss  3.5113515615792266 correct 50
Epoch  450  loss  3.392536187751817 correct 50
Epoch  460  loss  3.280366089292939 correct 50
Epoch  470  loss  3.174335030616491 correct 50
Epoch  480  loss  3.0751454660153374 correct 50
Epoch  490  loss  2.9818478056109585 correct 50
Epoch  500  loss  2.8935561207756995 correct 50



"Split"
<img width="243" height="723" alt="image" src="https://github.com/user-attachments/assets/c3c1fec2-4243-44c3-b8ce-d2602c3f87f2" />


PTS = 100
HIDDEN = 5
RATE = 0.5
    
Epoch  10  loss  63.86746161336832 correct 63
Epoch  20  loss  62.57390317681652 correct 63
Epoch  30  loss  60.97291900187527 correct 68
Epoch  40  loss  58.872853525271864 correct 77
Epoch  50  loss  56.52059214699987 correct 79
Epoch  60  loss  54.28227549414594 correct 78
Epoch  70  loss  52.34260617621541 correct 78
Epoch  80  loss  50.63230572672829 correct 78
Epoch  90  loss  49.13228540365734 correct 78
Epoch  100  loss  59.42657028169595 correct 67
Epoch  110  loss  53.725830167857424 correct 72
Epoch  120  loss  51.080913535907676 correct 73
Epoch  130  loss  50.39019042492583 correct 73
Epoch  140  loss  51.06619795637429 correct 73
Epoch  150  loss  50.58459157085289 correct 73
Epoch  160  loss  49.621976587585095 correct 80
Epoch  170  loss  48.297955977090396 correct 81
Epoch  180  loss  48.94994062033022 correct 81
Epoch  190  loss  47.908152198014015 correct 82
Epoch  200  loss  47.58442510174327 correct 83
Epoch  210  loss  46.586703140535164 correct 84
Epoch  220  loss  45.98901593657591 correct 84
Epoch  230  loss  40.77858535605098 correct 87
Epoch  240  loss  38.675536926887375 correct 88
Epoch  250  loss  36.92893428628239 correct 86
Epoch  260  loss  35.09773334553009 correct 86
Epoch  270  loss  46.30336268297033 correct 78
Epoch  280  loss  36.89660228005628 correct 82
Epoch  290  loss  32.48249957082668 correct 85
Epoch  300  loss  28.31935838917661 correct 87
Epoch  310  loss  24.23981743062202 correct 89
Epoch  320  loss  29.834776602208922 correct 84
Epoch  330  loss  22.990442855030317 correct 89
Epoch  340  loss  26.18707704828097 correct 87
Epoch  350  loss  25.846900194831278 correct 86
Epoch  360  loss  21.157960705940795 correct 92
Epoch  370  loss  19.83651312591961 correct 92
Epoch  380  loss  18.86167451482793 correct 93
Epoch  390  loss  18.781473978293086 correct 92
Epoch  400  loss  20.30192506576317 correct 92
Epoch  410  loss  17.22388720285319 correct 93
Epoch  420  loss  14.905157935408146 correct 93
Epoch  430  loss  17.73116214898936 correct 93
Epoch  440  loss  16.308968581780512 correct 93
Epoch  450  loss  16.84256720839102 correct 93
Epoch  460  loss  15.020810293912373 correct 93
Epoch  470  loss  13.98631696187532 correct 93
Epoch  480  loss  11.469497320866699 correct 94
Epoch  490  loss  8.917017006636193 correct 96
Epoch  500  loss  10.44123422477936 correct 95


"Circle"
<img width="241" height="720" alt="image" src="https://github.com/user-attachments/assets/40f0508b-6286-4a38-9f38-c8ad722fbcb7" />


PTS = 100
HIDDEN = 5
RATE = 0.4

Epoch  10  loss  60.26428339419598 correct 70
Epoch  20  loss  59.74353668938137 correct 70
Epoch  30  loss  59.305216526881686 correct 70
Epoch  40  loss  58.867087325129326 correct 70
Epoch  50  loss  58.4105255215147 correct 70
Epoch  60  loss  57.94783815535321 correct 70
Epoch  70  loss  57.47066289457915 correct 70
Epoch  80  loss  56.97197232806389 correct 70
Epoch  90  loss  56.396381168699286 correct 70
Epoch  100  loss  55.710885778380764 correct 70
Epoch  110  loss  54.865799905796045 correct 70
Epoch  120  loss  53.87092318423539 correct 70
Epoch  130  loss  52.71893240023516 correct 70
Epoch  140  loss  51.42374905139108 correct 70
Epoch  150  loss  50.169320737618115 correct 74
Epoch  160  loss  49.779453480244094 correct 77
Epoch  170  loss  53.9157558571103 correct 77
Epoch  180  loss  48.01042904191744 correct 78
Epoch  190  loss  47.305866794031914 correct 78
Epoch  200  loss  50.0326463826094 correct 80
Epoch  210  loss  47.97942945301196 correct 81
Epoch  220  loss  46.34568733840311 correct 81
Epoch  230  loss  45.01274326134405 correct 81
Epoch  240  loss  44.399900898767356 correct 81
Epoch  250  loss  43.72006120065733 correct 81
Epoch  260  loss  42.70521539706403 correct 82
Epoch  270  loss  42.509449350601635 correct 81
Epoch  280  loss  38.755675479834714 correct 82
Epoch  290  loss  36.589401292475806 correct 82
Epoch  300  loss  34.535069479823854 correct 87
Epoch  310  loss  32.57702573012557 correct 87
Epoch  320  loss  30.32287737590076 correct 87
Epoch  330  loss  28.41584324735484 correct 91
Epoch  340  loss  26.747582092025457 correct 91
Epoch  350  loss  26.136647093341278 correct 91
Epoch  360  loss  25.03406498491448 correct 90
Epoch  370  loss  24.17574250411611 correct 90
Epoch  380  loss  23.118367008576616 correct 91
Epoch  390  loss  23.183602525008656 correct 91
Epoch  400  loss  22.497827658430086 correct 91
Epoch  410  loss  23.67705241613206 correct 93
Epoch  420  loss  24.016090106617273 correct 92
Epoch  430  loss  26.536230732128185 correct 89
Epoch  440  loss  26.0733205747403 correct 89
Epoch  450  loss  22.908564694171325 correct 92
Epoch  460  loss  22.269471236117834 correct 92
Epoch  470  loss  29.684910971867854 correct 85
Epoch  480  loss  19.70967084070918 correct 93
Epoch  490  loss  17.681345362305773 correct 95
Epoch  500  loss  18.207874591388993 correct 93




