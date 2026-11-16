# Dagger with RxJava, Retrofit, MVP and Data Binding (Android)

Android sample that adds Android Data Binding to the MVP, Dagger, RxJava and Retrofit setup.

This is an older sample kept for reference. It is not actively maintained.

## What it shows

- Everything in the MVP sample, plus `dataBinding` enabled in the module
- A `TestAdapter` for the list, next to the `TestFragment`, `TestPresenter` and `TestView`
- Posts loaded from [JSONPlaceholder](https://jsonplaceholder.typicode.com) with Retrofit and RxJava 2

## Stack

Java, Dagger 2.14.1, RxJava 2.1.9, RxAndroid 2.0.2, Retrofit 2.3.0, Data Binding compiler 3.1.2,
`minSdkVersion 15`, `compileSdkVersion 27`.

## Run

Open the project in Android Studio and run the `app` module. It uses an older Android Gradle plugin (3.1.x) and `compileSdkVersion 27`, so Android Studio may ask you to update the Gradle wrapper and plugin.

## License

MIT. See [LICENSE](LICENSE).
