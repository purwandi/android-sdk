FROM androidsdk/android-28

RUN yes | sdkmanager \
    "build-tools;28.0.3" \
    "build-tools;28.0.2" \
    "build-tools;28.0.1" \
    "build-tools;28.0.0" \
    "ndk;21.0.6113669"

RUN sdkmanager --list_installed