```console
(venv_numina) $ numina-pixel_to_world --help
```

```{code-block} ansi-shell-session
:class: my-special-block no-copybutton

[38;5;208mUsage:[0m [38;5;244mnumina-pixel_to_world[0m [[36m-h[0m] [[36m--pixel[0m [38;5;36mPIXEL[0m] [[36m-e[0m [38;5;36mEXTNUM[0m] [[36m--extname[0m [38;5;36mEXTNAME[0m]
                             [[36m--wcskey[0m [38;5;36mWCSKEY[0m] [[36m--version[0m] [[36m--output-dir[0m [38;5;36mOUTPUT_DIR[0m] [[36m--no-color[0m]
                             [[36m--record[0m] [[36m--echo[0m] [[36m--log-level[0m [38;5;36m{DEBUG,INFO,WARNING,ERROR,CRITICAL}[0m]
                             [36minputfile[0m

[39mConvert pixel to world coordinates.[0m

[38;5;208mPositional Arguments:[0m
  [36minputfile[0m             [39mInput FITS file[0m

[38;5;208mOptions:[0m
  [36m-h[0m, [36m--help[0m            [39mshow this help message and exit[0m
  [36m--pixel[0m [38;5;36mPIXEL[0m         [39mWCS pixel coordinate (comma separated values)[0m
  [36m-e[0m, [36m--extnum[0m [38;5;36mEXTNUM[0m   [39mExtension number[0m
  [36m--extname[0m [38;5;36mEXTNAME[0m     [39mExtension name[0m
  [36m--wcskey[0m [38;5;36mWCSKEY[0m       [39mWCS key to use when multiple WCS are present in the FITS header[0m
  [36m--version[0m             [39mDisplay version information and exit[0m
  [36m--output-dir[0m [38;5;36mOUTPUT_DIR[0m
                        [39mOutput directory (default: .)[0m
  [36m--no-color[0m            [39mDisable color output[0m
  [36m--record[0m              [39mRecord terminal output[0m
  [36m--echo[0m                [39mDisplay full command line[0m
  [36m--log-level[0m [38;5;36m{DEBUG,INFO,WARNING,ERROR,CRITICAL}[0m
                        [39mSet the logging level[0m
```
