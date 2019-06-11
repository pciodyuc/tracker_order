# tracker_order
说明：
* 部分基于https://github.com/foolwood/benchmark_results
* 由于自己的其他需求后续会添加一些其他内容，请关注https://github.com/foolwood/benchmark_results

| Tracker   | AUC-CVPR2013| Precision-CVPR2013 | AUC-OTB100 | Precision-OTB100 | AUC-OTB50 | Precision-OTB50|DeepLearning|RealTime|      
| :---------: | :---------: | :----------: | :--------: | :--------: | :--------: | :--------: | :--------: | :--------: |
|     ECO     |  **0.709**   |        0.93        | **0.694**  |    **0.910**     |  *0.643*  |     *0.874*     |       Y       |    N(6)    |
|    MDNet    |   *0.708*    |      *0.948*       |  *0.678*   |     *0.909*      | **0.645** |    **0.890**    |       Y       |    N(1)    |
|    SANet    |    0.686     |      **0.95**      |   0.692    |      0.928       |     -     |        -        |       Y       |    N(1)    |
|  BranchOut  |              |                    |   0.678    |      0.917       |           |                 |       Y       |    N(1)    |
|    TCNN     |    0.682     |       0.937        |   0.654    |      0.884       |     -     |        -        |       Y       |    N(1)    |
|     TSN     |              |                    |   0.644    |      0.868       |   0.58    |      0.809      |       Y       |    N(1)    |
|     CRT     |      -       |         -          |   0.642    |      0.875       |   0.594   |      0.835      |       Y       |   N(1.3)   |
|    BACF     |    0.678     |                    |    0.63    |                  |           |                 |       N       |   Y(35)    |
|    MCPF     |    0.677     |       0.916        |   0.628    |      0.873       |           |                 |       Y       |   N(0.5)   |
|    CREST    |    0.673     |       0.908        |   0.623    |      0.837       |     -     |        -        |       Y       |    N(1)    |
|    C-COT    |    0.672     |       0.899        |   0.682    |        -         |     -     |        -        |       Y       |   N(0.3)   |
|     DNT     |    0.664     |       0.907        |   0.627    |      0.851       |     -     |        -        |       Y       |    N(5)    |
|    PTAV     |    0.663     |       0.894        |   0.635    |      0.849       |           |                 |       Y       |   Y(25)    |
|    ADNet    |    0.659     |       0.903        |   0.646    |       0.88       |           |                 |       Y       |    N(3)    |
|   DSiamM    |    0.656     |       0.891        |            |                  |           |                 |       Y       |   Y(25)    |
|    SINT+    |    0.655     |       0.882        |     -      |        -         |     -     |        -        |       Y       |    N(4)    |
|     DRT     |    0.655     |       0.892        |     -      |        -         |     -     |        -        |       Y       |   N(0.8)   |
|     RDT     |    0.654     |         -          |   0.603    |        -         |     -     |        -        |       Y       |   Y(43)    |
| SRDCFdecon  |    0.653     |        0.87        |   0.627    |      0.825       |   0.56    |      0.764      |       N       |    N(1)    |
|  DeepLMCF   |    0.643     |       0.892        |            |                  |           |                 |       Y       |    N(8)    |
|   MUSTer    |    0.641     |       0.865        |   0.575    |      0.774       |     -     |        -        |       N       |    N(4)    |
|  DeepSRDCF  |    0.641     |       0.849        |   0.635    |      0.851       |   0.56    |      0.772      |       Y       |   N(<1)    |
|    EAST     |    0.638     |                    |            |                  |           |                 |       Y       | Y(23/159)  |
|    SINT     |    0.635     |       0.851        |     -      |        -         |     -     |        -        |       Y       |    N(4)    |
|     LCT     |    0.628     |       0.848        |   0.562    |      0.762       |   0.492   |      0.691      |       N       |   Y(27)    |
|    SRDCF    |    0.626     |       0.838        |   0.598    |      0.789       |   0.539   |      0.732      |       N       |    N(5)    |
|    LMCF     |    0.624     |       0.839        |   0.568    |                  |           |                 |       N       |   Y(85)    |
|     SCF     |    0.623     |       0.874        |     -      |        -         |     -     |        -        |       N       |   Y(35)    |
|  Staple_CA  |    0.621     |       0.833        |   0.598    |       0.81       |           |                 |       N       |   Y(35)    |
|     RaF     |    0.615     |       0.919        |            |                  |           |                 |       Y       |    N(2)    |
|   SiamFC    |    0.612     |       0.815        |     -      |        -         |     -     |        -        |       Y       |   Y(58)    |
|     RFL     |              |                    |   0.581    |                  |           |                 |       Y       |   Y(15)    |
| CFNet_conv2 |    0.611     |       0.807        |   0.568    |      0.748       |   0.53    |      0.702      |       Y       |   Y(75)    |
| SiamFC_{3s} |    0.608     |       0.809        |     -      |        -         |     -     |        -        |       Y       |   Y(86)    |
|    ACFN     |    0.607     |        0.86        |   0.575    |      0.802       |           |                 |       Y       |   Y(15)    |
|     CF2     |    0.605     |       0.891        |   0.562    |      0.837       |   0.513   |      0.803      |       Y       |   N(11)    |
|     HDT     |    0.603     |       0.889        |   0.654    |      0.848       |   0.515   |      0.804      |       Y       |   N(10)    |
|   Staple    |     0.6      |       0.793        |   0.578    |      0.784       |     -     |        -        |       N       |   Y(80)    |
|   CSR-DCF   |    0.599     |        0.8         |   0.598    |      0.733       |           |                 |       N       |   Y(13)    |
|    FCNT     |    0.599     |       0.856        |     -      |        -         |     -     |        -        |       Y       |    N(1)    |
|   CNN-SVM   |    0.597     |       0.852        |   0.554    |      0.814       |   0.512   |      0.769      |       Y       |     N      |
|     SCT     |    0.595     |       0.845        |     -      |        -         |     -     |        -        |       Y       |   Y(40)    |
|   SO-DLT    |    0.595     |        0.81        |     -      |        -         |     -     |        -        |       Y       |     N      |
|     BIT     |    0.593     |       0.817        |     -      |        -         |     -     |        -        |       N       |   Y(45)    |
|   DLSSVM    |    0.589     |       0.829        |   0.541    |      0.767       |     -     |        -        |       Y       |   N(10)    |
|    SAMF     |    0.579     |       0.785        |   0.535    |      0.743       |     -     |        -        |       N       |    N(7)    |
|     RPT     |    0.577     |       0.805        |     -      |        -         |     -     |        -        |       N       |    N(4)    |
|    MEEM     |    0.566     |        0.83        |    0.53    |      0.781       |   0.473   |      0.712      |       N       |   N(10)    |
|    DSST     |    0.554     |       0.737        |    0.52    |      0.693       |   0.463   |      0.625      |       N       |   Y(24)    |
|     CNT     |    0.545     |       0.723        |     -      |        -         |     -     |        -        |       Y       |   N(1.5)   |
|    TGPR     |    0.529     |       0.766        |   0.458    |      0.643       |     -     |        -        |       N       |    N(1)    |
|     KCF     |    0.514     |        0.74        |   0.477    |      0.693       |   0.403   |      0.611      |       N       | Y(**172**) |
|   GOTURN    |    0.444     |        0.62        |   0.427    |      0.572       |     -     |        -        |       Y       |  Y(*165*)  |
