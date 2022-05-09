FROM androidsdk/android-31

RUN yes | sdkmanager \
    "build-tools;30.0.3" \
    "build-tools;30.0.2" \
    "build-tools;30.0.0" \
    "build-tools;31.0.0" \
    "ndk;21.4.7075529"

RUN sdkmanager --list_installed