# Astra Client — wydania

W tym repozytorium trzymamy wyłącznie **wydania** wbudowanego moda Astra
Launcher. Kliknij [Releases](https://github.com/v3nn7/astrabuiltin/releases),
żeby pobrać `astra-client-multiversion.jar`.

Launcher Astra sam pobiera najnowszy plik z `releases/latest` — aktualizacja
moda przebiega automatycznie, bez żadnych kliknięć w grze czy w launcherze.

## Skąd wziąć kod moda?

Kod źródłowy moda żyje w repozytorium launchera:

    astralauncher/src-tauri/builtin-mod

Build i publikacja wydania (wymagane prawo zapisu do tego repo):

    npm run mod:build     # buduje jara
    npm run mod:publish   # tworzy/wydaje release v<wersja>
