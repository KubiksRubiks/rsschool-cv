# Kubiks Rubiks

## Conacts

  * **Email** : KubiksGit@yandex.com
  * **Phone number** : +375 (29) 723-27-42
  * **Telegram** : @Kubiks_Rubiks
  * **GitHub** : [github.com/KubiksRubiks](https://github.com/KubiksRubiks)

## Summary

I'm an Eengineer for Automated Production Control Systems at the state enterprise X. I'm studying at the BSUIR master's degree in Radio Systems and Radio Technologies. I love biathlon and sports. I want to become an Android developer in order to write a sports application for myself for my needs. If I am motivated, then I have a wild interest in continuing, even when I can't.

## Skills

* **Programming Languages** : VBA, Java, Kotlin
* **IDE** : Visual Studio Code, Android Studio
* **Other software** : Adobe Photoshop CS6

## Code examples

```
object Utils {
    fun parseFullName(fullName: String?): Pair<String?, String?> = when {
        fullName?.trim() == null -> null to null
        fullName.trim().isEmpty() -> null to null
        else -> fullName.trim().split(" ").let { it.getOrNull(0) to it.getOrNull(1)
        }
    }

    fun toInitials(firstName: String?, lastName: String?): String? = when {
        (firstName?.trim().isNullOrEmpty() && lastName?.trim().isNullOrEmpty()) -> null
        (firstName != null && lastName.isNullOrEmpty()) ->
            firstName.trim().first().toString().toUpperCase()
        (firstName?.trim().isNullOrEmpty() && lastName != null) ->
            lastName.trim().first().toString().toUpperCase()
        else -> (firstName!!.trim().first().toString().toUpperCase() + lastName!!.trim().first().toString().toUpperCase())
    }
}    
```

## Experience

* Complete a course the SkillBranch community course on Kotlin [here](https://skill-branch.ru/dev-intensive-2019)  (only basic concepts, heavily truncated)
* no experience in commercial development

## Education

* __Higher Education__ :  
Belarusian State University of Informatick and Radioelectronics, specialization "Radio Engineering (Programmable Radio Electronic Means)" (2016 – 2020)  

* __Self Education__ :  
Google CodeLabs: Android __(in progress)__
SkillBranch: Android on Kotlin __(free сontent)__
Keddit — Intro: Learn Kotlin while developing an Android App __(in progress)__  

## English

* A2 (Pre-Intermediate)
* I have no conversational practice
