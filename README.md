<div align="center">
  <a href="https://github.com/RekuNote/RekuTools/">
    <img src="https://github.com/RekuNote/RekuTools/blob/main/icon.png?raw=true" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">RekuTools</h3>

  <p align="center">
    Quick 'n' Dirty tool for dumping fnkeys.pem & encoding Flipnotes from MP4.<br />
    Supports macOS & most popular Linux distributions.
    <br />
    © 2025 RexiMemo!
    <br />
    <br />
  </p>
</div>
<br />

## Usage
Set permissions so the user can execute:<br />
```chmod +x RekuTools```<br />
<br />
Prepare the script for dumping fnkeys.pem and run with:<br />
```./RekuTools --dump path/to/flipnotestudio.nds```<br />
<br />
Prepare the script for encoding flipnotes and run with:<br />
```./RekuTools --encode path/to/video.mp4```

## Notice:<br />
Ensure you have mpv installed. If you don't, the script will ask to install it for you.<br />
Ensure Flipnote Studio ```.nds``` file is USA region.<br />
Ensure MP4 files are 256x192 prior to encoding.<br />
For best results, ensure MP4 files are strictly black, white and blue OR black white and red prior to encoding.<br />
Both ```fnkeys.pem``` and encoded flipnote MP4s will be output to the same directory the script is in.<br />
