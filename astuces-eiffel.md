## Astuces pour les Linux de Gustave-Eiffel

> Toute nouvelle astuce est la bienvenue.

## Installer oh-my-zsh (terminal linter)

```
echo "export SHELL=/bin/zsh\nexec /bin/zsh -l" >> ~/.bashrc && sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
```

fait en sorte que bash exécute zsh en l'absence des privileges nécessaires pour faire de zsh le shell par défault puis installe oh-my-zsh

puis rouvrir un terminal

## Capture d'écran

mystérieusement, la touche impr-écran ne marche pas. Il faut donc run

```
gnome-screenshot -i
```
pour arriver au même résultat
