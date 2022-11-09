## Включение внешний линтер

Плагин IntelliJ Rust не обнаруживает все ошибки. Для этого он использует компилятор Rust. Пока вы изучаете Rust, полезно видеть ошибки по мере ввода. Чтобы иметь такое поведение, мы рекомендуем включить внешний линтер следующим образом:

1. Перейдите **Settings / Preferences | Languages & Frameworks | Rust | External Linters**.
2. Установите параметры следующим образом:
    - Выберите **Cargo check** в списке **External Tool:**;
    - Установите флажок **Run external linter to analyze code on the fly**.

![External Linters](images/external-linters.png)
3. Нажмите **OK**.

Как только вы это сделаете, %IDE_NAME% сообщит обо всех ошибках, обнаруженных плагином IntelliJ Rust или компилятором Rust.