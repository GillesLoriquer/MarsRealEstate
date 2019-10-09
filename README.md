# MarsRealEstate

Application simulant la location et l'achat de parcelles de Mars. Il s'agit de la mise en pratique de la lesson 8 [Connect to the Internet](https://classroom.udacity.com/courses/ud9012) de Google (Udacity)

## Concepts mis en oeuvre

* Appels REST avec Retrofit
* Moshi pour la désérialisation JSON
* Glide pour le chargement et le cache des images
* ViewModel
* LiveData
* Databinding avec binding adapters
* Navigation avec les SafeArgs

## Prérequis

* Android Studio

## Installation

Télécharger le .zip du projet, extraire le contenu dans le répertoire de votre choix et ouvrir ce répertoire dans Android Studio.

## Version SDK

* minSdkVersion 19
* targetSdkVersion 28

## Dépendances

```
ext {
    version_android_gradle_plugin = "3.3.2"
    version_core = "1.0.1"
    version_constraint_layout = "1.1.3"
    version_glide = "4.8.0"
    version_kotlin = "1.3.21"
    version_kotlin_coroutines = "1.1.0"
    version_lifecycle_extensions = "2.0.0"
    version_moshi = "1.8.0"
    version_navigation = "1.0.0"
    version_retrofit = "2.5.0"
    version_retrofit_coroutines_adapter = "0.9.2"
    version_recyclerview = "1.0.0"
}
```

* Kotlin
    * org.jetbrains.kotlin:kotlin-stdlib-jdk7:$version_kotlin

* Constraint Layout
    * androidx.constraintlayout:constraintlayout:$version_constraint_layout

* ViewModel and LiveData
    * androidx.lifecycle:lifecycle-extensions:$version_lifecycle_extensions

* Navigation
    * android.arch.navigation:navigation-fragment-ktx:$version_navigation
    * android.arch.navigation:navigation-ui-ktx:$version_navigation

* Core with Ktx
    * androidx.core:core-ktx:$version_core

* Retrofit
    * com.squareup.retrofit2:retrofit:$version_retrofit
    * com.squareup.retrofit2:converter-moshi:$version_retrofit
    * com.jakewharton.retrofit:retrofit2-kotlin-coroutines-adapter:$version_retrofit_coroutines_adapter

* Moshi (JSON Parser)
    * com.squareup.moshi:moshi:$version_moshi
    * com.squareup.moshi:moshi-kotlin:$version_moshi

* Corountine
    * org.jetbrains.kotlinx:kotlinx-coroutines-core:$version_kotlin_coroutines
    * org.jetbrains.kotlinx:kotlinx-coroutines-android:$version_kotlin_coroutines

* Glide
    * com.github.bumptech.glide:glide:$version_glide