# AccentColorizer-E11 For WindowsAppSDK File Explorer

Starting from 25309(Old Insiders Dev), Microsoft introduced WindowsAppSDK File Explorer. However, the location of icons for the new File Explorer was changed. This is why the original AccentColorizer-E11 is not working.
I edited a bit to make it work.

Based on Original [AccentColorizer-E11](https://github.com/krlvm/AccentColorizer-E11)

The program will run in background and recolorize the glyphs every time accent color is changed, but if you need to run it once and don't want to have it running in background, launch it with `-Apply` argument:
```
$ AccentColorizer-E11.exe -Apply
```

## How does it look with WASDK File Explorer?

![1](https://user-images.githubusercontent.com/83257329/230906135-73d453fb-b0ef-4607-b817-65b496b37bd9.png)
![2](https://user-images.githubusercontent.com/83257329/230906136-e58c4bf7-7e86-42fe-9be4-f4ae0c8a4710.png)
![3](https://user-images.githubusercontent.com/83257329/230906145-01e3f08d-c146-4433-aa94-62a2f6dd0664.png)
![4](https://user-images.githubusercontent.com/83257329/230906148-f7f39a47-7072-459a-9e34-1d6bfdef19c6.png)
