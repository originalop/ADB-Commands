# List connected devices
`adb devices`
# List system apps
`adb shell pm list packages -s -f`
# List non-system apps
`adb shell pm list packages -3`
# Uninstall apps
`pm uninstall --user 0 <package_name>`