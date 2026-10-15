```console
(venv_numina) $ numina-ximshow --help
```

```{code-block} ansi-shell-session
:class: my-special-block no-copybutton

[38;5;208mUsage:[0m [38;5;244mnumina-ximshow[0m [[36m-h[0m] [[36m--extnum[0m [38;5;36mEXTNUM[0m] [[36m--extname[0m [38;5;36mEXTNAME[0m] [[36m--z1z2[0m [38;5;36mZ1Z2[0m] [[36m--bbox[0m [38;5;36mBBOX[0m]
                      [[36m--firstpix[0m [38;5;36mFIRSTPIX[0m] [[36m--aspect[0m [38;5;36m{equal,auto}[0m] [[36m--xlabel[0m [38;5;36mXLABEL[0m]
                      [[36m--ylabel[0m [38;5;36mYLABEL[0m] [[36m--cmap[0m [38;5;36mCMAP[0m] [[36m--cbar-label[0m [38;5;36mCBAR_LABEL[0m]
                      [[36m--cbar_orientation[0m [38;5;36m{horizontal,vertical,None}[0m] [[36m--keystitle[0m [38;5;36mKEYSTITLE[0m]
                      [[36m--ds9reg[0m [38;5;36mDS9REG[0m] [[36m--geometry[0m [38;5;36mGEOMETRY[0m] [[36m--factor_macosx[0m [38;5;36mFACTOR_MACOSX[0m]
                      [[36m--pdffile[0m [38;5;36mPDFFILE[0m] [[36m--pngfile[0m [38;5;36mPNGFILE[0m] [[36m--figuredict[0m [38;5;36mFIGUREDICT[0m]
                      [[36m--debugplot[0m [38;5;36m{0,1,2,10,11,12,21,22}[0m]
                      [36mfilename[0m [[36mfilename[0m [36m...[0m]

[39mdescription: display FITS images[0m

[38;5;208mPositional Arguments:[0m
  [36mfilename[0m              [39mFITS file (wildcards allowed) or txt file with list of FITS files[0m

[38;5;208mOptions:[0m
  [36m-h[0m, [36m--help[0m            [39mshow this help message and exit[0m
  [36m--extnum[0m [38;5;36mEXTNUM[0m       [39mExtension number in input files (note that primary extension is 1 =[0m
                        [39mdefault value)[0m
  [36m--extname[0m [38;5;36mEXTNAME[0m     [39mExtension name in input file. Only works for a single file, not for a list[0m
                        [39mof files (use [0m[36m--extnum[0m[39m instead)[0m
  [36m--z1z2[0m [38;5;36mZ1Z2[0m           [39mtuple '[+/-z1, +/-z2]', minmax, zscale or None (=zscale)[0m
  [36m--bbox[0m [38;5;36mBBOX[0m           [39mbounding box tuple: nc1,nc2,ns1,ns2[0m
  [36m--firstpix[0m [38;5;36mFIRSTPIX[0m   [39mcoordinates of lower left pixel: nc0, ns0[0m
  [36m--aspect[0m [38;5;36m{equal,auto}[0m
                        [39maspect ratio (equal or auto)[0m
  [36m--xlabel[0m [38;5;36mXLABEL[0m       [39mX-axis label[0m
  [36m--ylabel[0m [38;5;36mYLABEL[0m       [39mY-axis label[0m
  [36m--cmap[0m [38;5;36mCMAP[0m           [39mcolor map[0m
  [36m--cbar-label[0m [38;5;36mCBAR_LABEL[0m
                        [39mcolor bar label[0m
  [36m--cbar_orientation[0m [38;5;36m{horizontal,vertical,None}[0m
                        [39mcolor bar orientation[0m
  [36m--keystitle[0m [38;5;36mKEYSTITLE[0m
                        [39mtuple of FITS keywords.format: key1,key2,...keyn.'format'[0m
  [36m--ds9reg[0m [38;5;36mDS9REG[0m       [39mds9 region file to be overplotted[0m
  [36m--geometry[0m [38;5;36mGEOMETRY[0m   [39mstring "xwidth,ywidth,xorigin,yorigin"[0m
  [36m--factor_macosx[0m [38;5;36mFACTOR_MACOSX[0m
                        [39mFactor to control the size of the plot on macOS (default=1.5)[0m
  [36m--pdffile[0m [38;5;36mPDFFILE[0m     [39mouput PDF file name[0m
  [36m--pngfile[0m [38;5;36mPNGFILE[0m     [39mouput PNG file name[0m
  [36m--figuredict[0m [38;5;36mFIGUREDICT[0m
                        [39mstring with dictionary of parameters for plt.figure()[0m
  [36m--debugplot[0m [38;5;36m{0,1,2,10,11,12,21,22}[0m
                        [39mInteger indicating plotting/debugging (default=12)[0m
```
