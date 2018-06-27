# yarn-run.plugin.zsh

> Autocompletion support for `yarn run`.

## How to install

### With [Oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

1. Clone this repository in oh-my-zsh's plugins directory:

        git clone https://github.com/mscolnick/yarn-run.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/yarn-run

2. Activate the plugin in `~/.zshrc`:

        plugins=( [plugins...] yarn-run)

3. Source `~/.zshrc`  to take changes into account:

        source ~/.zshrc

## Usage

Switch to a project with a `package.json` file:

    $ yarn run <TAB>
