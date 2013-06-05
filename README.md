# Temporary virtual Maven repository

This repository is a workaround for free artifacts not found on public repositories.

## Content list

 - `android:android:4.0.3_r3`
 - `com.actionbarsherlock:actionbarsherlock:4.2.0`
 - `com.google.android.analytics:analytics:1.4.2`
 - `com.google.android.admob:admob:6.2.1-r8`


# TODO

Check if those artifacts licenses allow redistribution. If not, remove them (fully, including from Git history) and provide a setup script for filling the local repository. Especially for Android artifacts which are usually installed by copy from local install of the Android SDK (see https://github.com/mosabua/maven-android-sdk-deployer).

