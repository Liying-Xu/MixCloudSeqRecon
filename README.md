# MixCloudSeqRecon

**Physics-informed synthesis and reconstruction of cloud-free reflectance sequences under mixed cloud conditions.**

MixCloudSeqRecon combines MixCloudSynth, which constructs paired cloudy and clear reflectance sequences, with MixCloudFormer for reconstructing sequences affected by thin and thick clouds.

## MixCloudSeqPairs Dataset

![Examples from the MixCloudSeqPairs dataset](mixcloudseqpairs-examples.png)

## Application (2025)

Monthly raw observations and reconstructed reflectance across six cities.

### Beijing

| | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|
| **Jan · Raw**<br><img src="application/beijing/01_raw_white.jpg" width="130"> | **Feb · Raw**<br><img src="application/beijing/02_raw_white.jpg" width="130"> | **Mar · Raw**<br><img src="application/beijing/03_raw_white.jpg" width="130"> | **Apr · Raw**<br><img src="application/beijing/04_raw_white.jpg" width="130"> | **May · Raw**<br><img src="application/beijing/05_raw_white.jpg" width="130"> | **Jun · Raw**<br><img src="application/beijing/06_raw_white.jpg" width="130"> |
| **Jul · Raw**<br><img src="application/beijing/07_raw_white.jpg" width="130"> | **Aug · Raw**<br><img src="application/beijing/08_raw_white.jpg" width="130"> | **Sep · Raw**<br><img src="application/beijing/09_raw_white.jpg" width="130"> | **Oct · Raw**<br><img src="application/beijing/10_raw_white.jpg" width="130"> | **Nov · Raw**<br><img src="application/beijing/11_raw_white.jpg" width="130"> | **Dec · Raw**<br><img src="application/beijing/12_raw_white.jpg" width="130"> |
| **Jan · Result**<br><img src="application/beijing/01_reconstruction_white.jpg" width="130"> | **Feb · Result**<br><img src="application/beijing/02_reconstruction_white.jpg" width="130"> | **Mar · Result**<br><img src="application/beijing/03_reconstruction_white.jpg" width="130"> | **Apr · Result**<br><img src="application/beijing/04_reconstruction_white.jpg" width="130"> | **May · Result**<br><img src="application/beijing/05_reconstruction_white.jpg" width="130"> | **Jun · Result**<br><img src="application/beijing/06_reconstruction_white.jpg" width="130"> |
| **Jul · Result**<br><img src="application/beijing/07_reconstruction_white.jpg" width="130"> | **Aug · Result**<br><img src="application/beijing/08_reconstruction_white.jpg" width="130"> | **Sep · Result**<br><img src="application/beijing/09_reconstruction_white.jpg" width="130"> | **Oct · Result**<br><img src="application/beijing/10_reconstruction_white.jpg" width="130"> | **Nov · Result**<br><img src="application/beijing/11_reconstruction_white.jpg" width="130"> | **Dec · Result**<br><img src="application/beijing/12_reconstruction_white.jpg" width="130"> |

### Harbin

| | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|
| **Jan · Raw**<br><img src="application/harbin/01_raw_white.jpg" width="130"> | **Feb · Raw**<br><img src="application/harbin/02_raw_white.jpg" width="130"> | **Mar · Raw**<br><img src="application/harbin/03_raw_white.jpg" width="130"> | **Apr · Raw**<br><img src="application/harbin/04_raw_white.jpg" width="130"> | **May · Raw**<br><img src="application/harbin/05_raw_white.jpg" width="130"> | **Jun · Raw**<br><img src="application/harbin/06_raw_white.jpg" width="130"> |
| **Jul · Raw**<br><img src="application/harbin/07_raw_white.jpg" width="130"> | **Aug · Raw**<br><img src="application/harbin/08_raw_white.jpg" width="130"> | **Sep · Raw**<br><img src="application/harbin/09_raw_white.jpg" width="130"> | **Oct · Raw**<br><img src="application/harbin/10_raw_white.jpg" width="130"> | **Nov · Raw**<br><img src="application/harbin/11_raw_white.jpg" width="130"> | **Dec · Raw**<br><img src="application/harbin/12_raw_white.jpg" width="130"> |
| **Jan · Result**<br><img src="application/harbin/01_reconstruction_white.jpg" width="130"> | **Feb · Result**<br><img src="application/harbin/02_reconstruction_white.jpg" width="130"> | **Mar · Result**<br><img src="application/harbin/03_reconstruction_white.jpg" width="130"> | **Apr · Result**<br><img src="application/harbin/04_reconstruction_white.jpg" width="130"> | **May · Result**<br><img src="application/harbin/05_reconstruction_white.jpg" width="130"> | **Jun · Result**<br><img src="application/harbin/06_reconstruction_white.jpg" width="130"> |
| **Jul · Result**<br><img src="application/harbin/07_reconstruction_white.jpg" width="130"> | **Aug · Result**<br><img src="application/harbin/08_reconstruction_white.jpg" width="130"> | **Sep · Result**<br><img src="application/harbin/09_reconstruction_white.jpg" width="130"> | **Oct · Result**<br><img src="application/harbin/10_reconstruction_white.jpg" width="130"> | **Nov · Result**<br><img src="application/harbin/11_reconstruction_white.jpg" width="130"> | **Dec · Result**<br><img src="application/harbin/12_reconstruction_white.jpg" width="130"> |

### Kunming

| | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|
| **Jan · Raw**<br><img src="application/kunming/01_raw_white.jpg" width="130"> | **Feb · Raw**<br><img src="application/kunming/02_raw_white.jpg" width="130"> | **Mar · Raw**<br><img src="application/kunming/03_raw_white.jpg" width="130"> | **Apr · Raw**<br><img src="application/kunming/04_raw_white.jpg" width="130"> | **May · Raw**<br><img src="application/kunming/05_raw_white.jpg" width="130"> | **Jun · Raw**<br><img src="application/kunming/06_raw_white.jpg" width="130"> |
| **Jul · Raw**<br><img src="application/kunming/07_raw_white.jpg" width="130"> | **Aug · Raw**<br><img src="application/kunming/08_raw_white.jpg" width="130"> | **Sep · Raw**<br><img src="application/kunming/09_raw_white.jpg" width="130"> | **Oct · Raw**<br><img src="application/kunming/10_raw_white.jpg" width="130"> | **Nov · Raw**<br><img src="application/kunming/11_raw_white.jpg" width="130"> | **Dec · Raw**<br><img src="application/kunming/12_raw_white.jpg" width="130"> |
| **Jan · Result**<br><img src="application/kunming/01_reconstruction_white.jpg" width="130"> | **Feb · Result**<br><img src="application/kunming/02_reconstruction_white.jpg" width="130"> | **Mar · Result**<br><img src="application/kunming/03_reconstruction_white.jpg" width="130"> | **Apr · Result**<br><img src="application/kunming/04_reconstruction_white.jpg" width="130"> | **May · Result**<br><img src="application/kunming/05_reconstruction_white.jpg" width="130"> | **Jun · Result**<br><img src="application/kunming/06_reconstruction_white.jpg" width="130"> |
| **Jul · Result**<br><img src="application/kunming/07_reconstruction_white.jpg" width="130"> | **Aug · Result**<br><img src="application/kunming/08_reconstruction_white.jpg" width="130"> | **Sep · Result**<br><img src="application/kunming/09_reconstruction_white.jpg" width="130"> | **Oct · Result**<br><img src="application/kunming/10_reconstruction_white.jpg" width="130"> | **Nov · Result**<br><img src="application/kunming/11_reconstruction_white.jpg" width="130"> | **Dec · Result**<br><img src="application/kunming/12_reconstruction_white.jpg" width="130"> |

### Wuhan

| | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|
| **Jan · Raw**<br><img src="application/wuhan/01_raw_white.jpg" width="130"> | **Feb · Raw**<br><img src="application/wuhan/02_raw_white.jpg" width="130"> | **Mar · Raw**<br><img src="application/wuhan/03_raw_white.jpg" width="130"> | **Apr · Raw**<br><img src="application/wuhan/04_raw_white.jpg" width="130"> | **May · Raw**<br><img src="application/wuhan/05_raw_white.jpg" width="130"> | **Jun · Raw**<br><img src="application/wuhan/06_raw_white.jpg" width="130"> |
| **Jul · Raw**<br><img src="application/wuhan/07_raw_white.jpg" width="130"> | **Aug · Raw**<br><img src="application/wuhan/08_raw_white.jpg" width="130"> | **Sep · Raw**<br><img src="application/wuhan/09_raw_white.jpg" width="130"> | **Oct · Raw**<br><img src="application/wuhan/10_raw_white.jpg" width="130"> | **Nov · Raw**<br><img src="application/wuhan/11_raw_white.jpg" width="130"> | **Dec · Raw**<br><img src="application/wuhan/12_raw_white.jpg" width="130"> |
| **Jan · Result**<br><img src="application/wuhan/01_reconstruction_white.jpg" width="130"> | **Feb · Result**<br><img src="application/wuhan/02_reconstruction_white.jpg" width="130"> | **Mar · Result**<br><img src="application/wuhan/03_reconstruction_white.jpg" width="130"> | **Apr · Result**<br><img src="application/wuhan/04_reconstruction_white.jpg" width="130"> | **May · Result**<br><img src="application/wuhan/05_reconstruction_white.jpg" width="130"> | **Jun · Result**<br><img src="application/wuhan/06_reconstruction_white.jpg" width="130"> |
| **Jul · Result**<br><img src="application/wuhan/07_reconstruction_white.jpg" width="130"> | **Aug · Result**<br><img src="application/wuhan/08_reconstruction_white.jpg" width="130"> | **Sep · Result**<br><img src="application/wuhan/09_reconstruction_white.jpg" width="130"> | **Oct · Result**<br><img src="application/wuhan/10_reconstruction_white.jpg" width="130"> | **Nov · Result**<br><img src="application/wuhan/11_reconstruction_white.jpg" width="130"> | **Dec · Result**<br><img src="application/wuhan/12_reconstruction_white.jpg" width="130"> |

### Xining

| | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|
| **Jan · Raw**<br><img src="application/xining/01_raw_white.jpg" width="130"> | **Feb · Raw**<br><img src="application/xining/02_raw_white.jpg" width="130"> | **Mar · Raw**<br><img src="application/xining/03_raw_white.jpg" width="130"> | **Apr · Raw**<br><img src="application/xining/04_raw_white.jpg" width="130"> | **May · Raw**<br><img src="application/xining/05_raw_white.jpg" width="130"> | **Jun · Raw**<br><img src="application/xining/06_raw_white.jpg" width="130"> |
| **Jul · Raw**<br><img src="application/xining/07_raw_white.jpg" width="130"> | **Aug · Raw**<br><img src="application/xining/08_raw_white.jpg" width="130"> | **Sep · Raw**<br><img src="application/xining/09_raw_white.jpg" width="130"> | **Oct · Raw**<br><img src="application/xining/10_raw_white.jpg" width="130"> | **Nov · Raw**<br><img src="application/xining/11_raw_white.jpg" width="130"> | **Dec · Raw**<br><img src="application/xining/12_raw_white.jpg" width="130"> |
| **Jan · Result**<br><img src="application/xining/01_reconstruction_white.jpg" width="130"> | **Feb · Result**<br><img src="application/xining/02_reconstruction_white.jpg" width="130"> | **Mar · Result**<br><img src="application/xining/03_reconstruction_white.jpg" width="130"> | **Apr · Result**<br><img src="application/xining/04_reconstruction_white.jpg" width="130"> | **May · Result**<br><img src="application/xining/05_reconstruction_white.jpg" width="130"> | **Jun · Result**<br><img src="application/xining/06_reconstruction_white.jpg" width="130"> |
| **Jul · Result**<br><img src="application/xining/07_reconstruction_white.jpg" width="130"> | **Aug · Result**<br><img src="application/xining/08_reconstruction_white.jpg" width="130"> | **Sep · Result**<br><img src="application/xining/09_reconstruction_white.jpg" width="130"> | **Oct · Result**<br><img src="application/xining/10_reconstruction_white.jpg" width="130"> | **Nov · Result**<br><img src="application/xining/11_reconstruction_white.jpg" width="130"> | **Dec · Result**<br><img src="application/xining/12_reconstruction_white.jpg" width="130"> |

**Code will be released upon acceptance of the paper.**
