# TinyCAD For Mac
TinyCAD is a particularly useful Windows program that was actually at the core of circuit diagram development for my Water Cleanup Bot. I own a MacBook Pro M1 Max 16", a very powerful machine, but it could not run this app directly, so I pulled out Porting Kit and easily made it run as a portable app. Beware, though. The extracted app is more than 1 GB, which may take some time to extract and move to the Applications folder.

Note: After extracting and dragging the app to the Applications folder, run
```
xattr -d com.apple.quarantine /Applications/TinyCAD.app
```
in the terminal because this verifies the app, since this app is not signed.
