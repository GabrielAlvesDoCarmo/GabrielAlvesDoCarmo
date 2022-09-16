### Hi I'm Gabriel Alves 👋
![visitors](https://visitor-badge.laobi.icu/badge?page_id=GabrielAlvesDoCarmo)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://github.com/ellerbrock/open-source-badge/)
```kotlin
    enum class Level{
        JUNIOR,PLENO,SENIOR
    }
    class SoftwareEngineer(
        val name : String,
        val age : Int,
        val currentProfession : String,
        val languagesPrograming : ArrayList<Triple<String,String,Level>>,
        val framework : ArrayList<Pair<String,String>>,
        val studying : ArrayList<String>,
        val forTheFuture : ArrayList<String>,
        val dataBase : ArrayList<String>,
        val tools : ArrayList<String>
    )
    
    val mobileDeveloper : SoftwareEngineer = SoftwareEngineer(
        name = "Gabriel Alves",
        age = 25 ,
        currentProfession = "Software Engineer",
        languagesPrograming = arrayListOf(
            Triple("Java","60%",Level.PLENO),
            Triple("Kotlin","80%",Level.PLENO),
            Triple("Swift","30%",Level.JUNIOR),
            Triple("JavaScript","40%",Level.JUNIOR),
            Triple("Python","40%",Level.JUNIOR),
        ),
        framework = arrayListOf(
            Pair("React-Native","50%"),
            Pair("Flutter","15%"),
            Pair("Xamarin","<5%"),
        ),
        studying = arrayListOf(
            "Flutter","React-Native","Xamarin","Swift","Python"
        ),
        forTheFuture = arrayListOf(
            "GO","Typescript","Ionic","Angular","Vue"
        ),
        dataBase = arrayListOf(
            "Realtime","Sql","Sqlite","Mongo","MySql","Oracle","SqlServer"
        ),
        tools = arrayListOf(
            "Android Studio","VSCode","Visual Studio","Pycharm","Git","Github","Gitlab"
        )
    )
```

<!--
**GabrielAlvesDoCarmo/GabrielAlvesDoCarmo** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
