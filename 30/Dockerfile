FROM androidsdk/android-30

RUN yes | sdkmanager \
    "build-tools;30.0.3" \
    "build-tools;30.0.2" \
    "build-tools;30.0.0" \
    "ndk;21.0.6113669"

RUN sdkmanager --list_installed