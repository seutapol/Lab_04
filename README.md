# Lab 04 — Event Handling & Reusable Components

**Task 1 — RegistrationForm**
React-те тіркеу формасы жасалды. Input мәндері `useState` арқылы басқарылды (controlled component). Әр өзгерісте валидация тексеріледі: аты (≥2 символ), email (дұрыс формат), жас (18+). `preventDefault()` қолданылып, қате болмаса "Registration successful" хабарламасы көрсетіледі.

**Task 2 — Refactoring Components**
Бір үлкен компонент бірнеше қайта қолданылатын компоненттерге бөлінді: `AddArticle`, `ArticleList`, `ArticleItem`. Негізгі күй ата-аналық компонентте сақталады, ал `ArticleItem` өзінің ашылу күйін `useState` арқылы өзі басқарады.

