# List connected devices
`adb devices`
# List system apps
`adb shell pm list packages -s -f`
# List non-system apps
`adb shell pm list packages -3`
# Uninstall apps
`adb shell pm uninstall --user 0 com.android.chrome`
# Create new user
`adb shell pm create-user <username>`
- This would return ID which is useful for switching
# Switch user
`adb shell am switch-user <user-id>`
# Search apps
`adb shell pm list packages | findstr <App_Name>`