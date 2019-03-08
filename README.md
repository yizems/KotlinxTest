# KotlinxTest


此项目主要用于验证 kotlinx 在 include library 中的 id的时候,是否能够正常运行,目前为 Unresolved reference bug:

[stackoverflow](https://stackoverflow.com/questions/48378696/unresolved-reference-for-synthetic-view-when-layout-is-in-library-module)

[KT tracker](https://youtrack.jetbrains.com/issue/KT-22430)

顺便说句,该问题 已经发现了一年半多,至今没有修复,呵呵


Android Studio was able to find layout in `library` module.
See [MainActivity](https://github.com/mjurkus/KotlinxTest/blob/master/app/src/main/java/com/example/kotlinxtest/MainActivity.kt)

`import kotlinx.android.synthetic.main.layout_in_library.*`

But, when trying to assemble project task fails with error:
```
/app/src/main/java/com/example/kotlinxtest/MainActivity.kt
Error:(6, 40) Unresolved reference: layout_in_library
Error:(14, 10) Unresolved reference: text_view
```
