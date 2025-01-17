#Основы
# Определение
<span style="color:crimson"><b>Rust</b></span> - это мультипарадигменный язык программирования общего назначения.

# Ключевые особенности безопасности

1. **Управление памятью без сборщика мусора**: Rust использует систему [[Объясните, что такое ownership(владение) в Rust.| |владения(ownership)]] и [[Расскажите о правилах borrowing(заимствование) в Rust.| заимствования(borrowing)]], которая обеспечивает безопасность памяти без необходимости в сборщике мусора.
2. **Предотвращение гонок данных**: Система владения также помогает предотвратить проблемы параллельного программирования, такие как гонки данных.
4. **Отсутствие неопределенного поведения**: Rust гарантирует, что программы не будут иметь неопределенного поведения, которое часто является источником уязвимостей.
5. **Строгая система типов**: Помогает обнаруживать многие ошибки на этапе компиляции.
6. **Безопасные абстракции**: Rust позволяет создавать абстракции с нулевой стоимостью, которые не снижают производительность.
7. **Проверки во время выполнения**: Rust включает проверки переполнения и доступа к массивам, которые можно отключить для повышения производительности.