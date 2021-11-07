FROM androidsdk/android-29

RUN yes | sdkmanager \
    "build-tools;29.0.3" \
    "build-tools;29.0.2" \
    "build-tools;29.0.1" \
    "build-tools;29.0.0" \
    "ndk;21.0.6113669"

RUN sdkmanager --list_installed