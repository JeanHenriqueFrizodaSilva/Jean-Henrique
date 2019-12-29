<style name="AppTheme" parent="Theme.MaterialComponents.DayNight">int currentNightMode = configuration.uiMode & Configuration.UI_MODE_NIGHT_MASK;
switch (currentNightMode) {
    case Configuration.UI_MODE_NIGHT_NO:
        // Night mode is not active, we're using the light theme
        break;
    case Configuration.UI_MODE_NIGHT_YES:
        // Night mode is active, we're using dark theme
        break;
}<activity
    android:name=".MyActivity"
    android:configChanges="uiMode" />}<activity
    android:name=".MyActivity"
    android:configChanges="uiMode" />
}?attr/colorOnSurface
}AppCompatDelegate.setDefaultNightMode(MODE_NIGHT_NO MODE_NIGHT_YES MODE_NIGHT_FOLLOW_SYSTEM)
}android:forceDarkThemeAllowed: 
>true
>false
