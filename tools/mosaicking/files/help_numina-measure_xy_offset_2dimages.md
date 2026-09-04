```console
(venv_numina) $ numina-measure_xy_offset_2dimages --help
```

```{code-block} ansi-shell-session
:class: my-special-block no-copybutton

[38;5;208mUsage:[0m [38;5;244mnumina-measure_xy_offset_2dimages[0m [[36m-h[0m] [[36m--image1[0m [38;5;36mIMAGE1[0m]
                                         [[36m--image2[0m [38;5;36mIMAGE2[0m] [[36m--extnum1[0m [38;5;36mEXTNUM1[0m]
                                         [[36m--extnum2[0m [38;5;36mEXTNUM2[0m]
                                         [[36m--subtract-background[0m]
                                         [[36m--rescale-to-01[0m] [[36m--method[0m [38;5;36m{1,2}[0m]
                                         [[36m--plots[0m] [[36m--test[0m]
                                         [[36m--test-fwhm[0m [38;5;36mTEST_FWHM[0m]
                                         [[36m--test-amplitude[0m [38;5;36mTEST_AMPLITUDE[0m]
                                         [[36m--test-background[0m [38;5;36mTEST_BACKGROUND[0m]
                                         [[36m--test-noise[0m [38;5;36mTEST_NOISE[0m]
                                         [[36m--test-xoffset[0m [38;5;36mTEST_XOFFSET[0m]
                                         [[36m--test-yoffset[0m [38;5;36mTEST_YOFFSET[0m]
                                         [[36m--test-num-nans[0m [38;5;36mTEST_NUM_NANS[0m]
                                         [[36m--test-seed[0m [38;5;36mTEST_SEED[0m]
                                         [[36m--save-test-images[0m]
                                         [[36m--output-dir[0m [38;5;36mOUTPUT_DIR[0m] [[36m--record[0m]
                                         [[36m--echo[0m] [[36m--version[0m]
                                         [[36m--log-level[0m [38;5;36m{DEBUG,INFO,WARNING,ERROR,CRITICAL}[0m]

[39mDetermine (X,Y) offsets between 2 2D images using cross-correlation.[0m

[38;5;208mOptions:[0m
  [36m-h[0m, [36m--help[0m            [39mshow this help message and exit[0m
  [36m--image1[0m [38;5;36mIMAGE1[0m       [39mPath to the first 2D image[0m
  [36m--image2[0m [38;5;36mIMAGE2[0m       [39mPath to the second 2D image[0m
  [36m--extnum1[0m [38;5;36mEXTNUM1[0m     [39mExtension number for the first image (default: 0)[0m
  [36m--extnum2[0m [38;5;36mEXTNUM2[0m     [39mExtension number for the second image (default: 0)[0m
  [36m--subtract-background[0m
                        [39mSubtract median background from images[0m
  [36m--rescale-to-01[0m       [39mRescale images to the range [0, 1] before computing[0m
                        [39mcross-correlation[0m
  [36m--method[0m [38;5;36m{1,2}[0m        [39mMethod (1: scipy (default), 2: skimage)[0m
  [36m--plots[0m               [39mGenerate plots of the images and cross-correlation[0m
  [36m--test[0m                [39mRun test mode with synthetic images[0m
  [36m--test-fwhm[0m [38;5;36mTEST_FWHM[0m
                        [39mFWHM of the synthetic Gaussian star (default: 10.0)[0m
  [36m--test-amplitude[0m [38;5;36mTEST_AMPLITUDE[0m
                        [39mAmplitude of the synthetic Gaussian star (default:[0m
                        [39m1000.0)[0m
  [36m--test-background[0m [38;5;36mTEST_BACKGROUND[0m
                        [39mBackground level of the synthetic images (default:[0m
                        [39m100.0)[0m
  [36m--test-noise[0m [38;5;36mTEST_NOISE[0m
                        [39mNoise level of the synthetic images (default: 5.0)[0m
  [36m--test-xoffset[0m [38;5;36mTEST_XOFFSET[0m
                        [39mX offset of the synthetic images (default: 5.0)[0m
  [36m--test-yoffset[0m [38;5;36mTEST_YOFFSET[0m
                        [39mY offset of the synthetic images (default: 3.0)[0m
  [36m--test-num-nans[0m [38;5;36mTEST_NUM_NANS[0m
                        [39mNumber of NaN pixels to insert in each synthetic image[0m
                        [39m(default: 20)[0m
  [36m--test-seed[0m [38;5;36mTEST_SEED[0m
                        [39mRandom seed for synthetic images (default: 1234)[0m
  [36m--save-test-images[0m    [39mSave synthetic images to FITS files[0m
  [36m--output-dir[0m [38;5;36mOUTPUT_DIR[0m
                        [39mOutput directory (default: .)[0m
  [36m--record[0m              [39mRecord terminal output[0m
  [36m--echo[0m                [39mDisplay full command line[0m
  [36m--version[0m             [39mDisplay version[0m
  [36m--log-level[0m [38;5;36m{DEBUG,INFO,WARNING,ERROR,CRITICAL}[0m
                        [39mSet the logging level[0m
```
