```console
(venv_numina) $ numina-generate_mosaic_of_2d_images --help
```

```{code-block} ansi-shell-session
:class: my-special-block no-copybutton

[38;5;208mUsage:[0m [38;5;244mnumina-generate_mosaic_of_2d_images[0m [[36m-h[0m] [[36m--reproject-method[0m [38;5;36m{interp,adaptive,exact}[0m]
                                           [[36m--extname-image[0m [38;5;36mEXTNAME_IMAGE[0m]
                                           [[36m--extname-mask[0m [38;5;36mEXTNAME_MASK[0m]
                                           [[36m--combination-function[0m [38;5;36m{mean,median,sum,std,sigmaclip_mean,sigmaclip_median,sigmaclip_stddev}[0m]
                                           [[36m--output-3D-stack[0m [38;5;36mOUTPUT_3D_STACK[0m] [[36m--version[0m]
                                           [[36m--output-dir[0m [38;5;36mOUTPUT_DIR[0m] [[36m--no-color[0m] [[36m--record[0m]
                                           [[36m--echo[0m]
                                           [[36m--log-level[0m [38;5;36m{DEBUG,INFO,WARNING,ERROR,CRITICAL}[0m]
                                           [36minput_list[0m [36moutput_filename[0m

[39mGenerate mosaic of 2D images[0m

[38;5;208mPositional Arguments:[0m
  [36minput_list[0m            [39mTXT file with list of 2D images to be combined[0m
  [36moutput_filename[0m       [39mfilename of output FITS image[0m

[38;5;208mOptions:[0m
  [36m-h[0m, [36m--help[0m            [39mshow this help message and exit[0m
  [36m--reproject-method[0m [38;5;36m{interp,adaptive,exact}[0m
                        [39mReprojection method (interp, adaptive, exact)[0m
  [36m--extname-image[0m [38;5;36mEXTNAME_IMAGE[0m
                        [39mExtension name for image in input files. Default value: PRIMARY[0m
  [36m--extname-mask[0m [38;5;36mEXTNAME_MASK[0m
                        [39mExtension name for mask in input files. Default 'None': use np.nan in[0m
                        [39mimage[0m
  [36m--combination-function[0m [38;5;36m{mean,median,sum,std,sigmaclip_mean,sigmaclip_median,sigmaclip_stddev}[0m
                        [39mCombination function. Default: mean[0m
  [36m--output-3D-stack[0m [38;5;36mOUTPUT_3D_STACK[0m
                        [39mfilename for stacked 3D array. Default None[0m
  [36m--version[0m             [39mDisplay version information and exit[0m
  [36m--output-dir[0m [38;5;36mOUTPUT_DIR[0m
                        [39mOutput directory (default: .)[0m
  [36m--no-color[0m            [39mDisable color output[0m
  [36m--record[0m              [39mRecord terminal output[0m
  [36m--echo[0m                [39mDisplay full command line[0m
  [36m--log-level[0m [38;5;36m{DEBUG,INFO,WARNING,ERROR,CRITICAL}[0m
                        [39mSet the logging level[0m
```
