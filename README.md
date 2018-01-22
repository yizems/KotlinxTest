# KotlinxTest

Android Studio was able to find layout in `library` module.
See [MainActivity](https://github.com/mjurkus/KotlinxTest/blob/master/app/src/main/java/com/example/kotlinxtest/MainActivity.kt)

`import kotlinx.android.synthetic.main.layout_in_library.*`

But, when trying to assemble project task fails with error:
```
/app/src/main/java/com/example/kotlinxtest/MainActivity.kt
Error:(6, 40) Unresolved reference: layout_in_library
Error:(14, 10) Unresolved reference: text_view
```
