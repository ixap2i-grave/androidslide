### AndroidStudioの構成部品とKotlinについて
for shinjuku-mokumoku28

---

### 2 page


- 今週触ったAndroidStudioの部品についてまとめました
- Kotlinのいいと思ったところも紹介します

---?image=android_dir.png&size=contain
---?image=android_mark.png&size=contain

---

### Model

 - MainActivityはAndroidアプリを構成する最も基本的なクラス
 -  main関数のように他の関数を呼び出す振る舞いをする

 - 致命的なエラーでない限り、途中で例外が発生しても処理は終了せず、
後続の処理が続いていく性質がある。(UX向上のため)


 - データはアクティビティの変化で失われる事はない

---

### View

 - xmlでマークアップしていく
 -  android:id="@+id/user_input_text"など特有のprefix

があり、viewのidから入力した文字列などを受け取る


---


---?image=kotlin.png&size=contain


---

- 型推論

 -　val sample = "data"
 -  val sample: String = "data"


- Pair

