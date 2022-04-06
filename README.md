# visiting_card

DEPENDENCIES

App level gradle

dependencies {

    apply plugin: 'kotlin-android-extensions'
    //noinspection GradleCompatible
    implementation 'com.android.support:appcompat-v7:28.0.0'
    implementation 'androidx.constraintlayout:constraintlayout:2.1.3'
    implementation 'com.android.support.constraint:constraint-layout:2.0.4'
    testImplementation 'junit:junit:4.13.2'
    androidTestImplementation 'com.android.support.test:runner:1.0.2'
    androidTestImplementation 'com.android.support.test.espresso:espresso-core:3.0.2'
}

Gradle properties

android.useAndroidX=true
android.enableJetifier=true
