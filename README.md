# Range Valorant

[Download the playable Windows build](https://github.com/walthough/VALORANT-Range/releases/latest)

On the release page, download **Range_Valorant_Windows_v1.0.zip** from **Assets**.

1. Extract the entire ZIP.
2. Open the extracted `Windows` folder.
3. Run `Range_Valorant.exe` and keep all the other folders and files together.

If Windows prerequisites are needed, run `Windows/Engine/Extras/Redist/en-us/vc_redist.x64.exe`.

## Downloading from the repository

The playable build is provided as a release asset. GitHub's **Code → Download ZIP** and automatic **Source code** archives may contain Git LFS text pointers instead of the large game executable and data files. Trying to run a pointer file can produce a Windows incompatibility error.

If you prefer cloning the repository, install Git LFS and run:

```powershell
git lfs install
git clone https://github.com/walthough/VALORANT-Range.git
cd VALORANT-Range
git lfs pull
```

Then run `Windows/Range_Valorant.exe`.

This Windows shipping build includes the window-wall collision fix.
