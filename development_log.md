# Журнал Разработки

Здесь будут записываться основные изменения и доработки проекта.

## Дата: [Вставь сегодняшнюю дату]
 
*   **Портал:** Добавлена анимация пульсации (изменение размера и цвета) при приближении игрока. 
    *   Использован `Tween` для анимации.
    *   Добавлена отдельная `Area2D` (`ProximityDetector`) для определения зоны приближения.
    *   Параметры анимации (масштаб, длительность, цвет) вынесены в `@export` переменные в `portal.gd`. 