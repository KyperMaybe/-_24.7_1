# УПП_24.7_1

Атмосферный 2D пазл-платформер в духе Ori, Child of Light и Limbo.

## Project Goal

Медитативный 2D пазл-платформер с уникальным визуалом и световыми головоломками.

## Инструкция по запуску

### Требования

- **Windows 10 или новее**
- **Visual Studio 2026** с установленным workload **Desktop development with C++**

### Клонирование

```bash
git clone --recurse-submodules https://github.com/KyperMaybe/-_24.7_1.git
cd -_24.7_1
```

Если проект уже склонирован без движка:
```bash
git submodule update --init --recursive
```

### Сборка и запуск

1. Откройте `FairyEngine.slnx` в Visual Studio 2026.
2. Выберите конфигурацию `Debug` или `Release` и платформу `x64`.
3. **Build → Build Solution** (или `Ctrl+Shift+B`).
4. **Debug → Start Without Debugging** (или `Ctrl+F5`).

> Ресурсы игры лежат в `FairyEngine/assets` и должны сохранять эту структуру относительно исполняемого файла.
