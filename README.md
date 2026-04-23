# gazperi-lab

Marketplace de plugins do Claude Code mantido pelo [Claude Lab](https://github.com/alfredogazperi) do Alfredo Gazperi. Ferramentas em português pt-BR, calibradas pelo uso diário.

## Instalação

No Claude Code:

```
/plugin marketplace add alfredogazperi/gazperi-lab
/plugin install cavernoso@gazperi-lab
```

## Plugins

### [cavernoso](https://github.com/alfredogazperi/cavernoso)

Modo de comunicação ultracomprimido em pt-BR. Fala como cavernoso, corta ~75% dos tokens mantendo precisão técnica total.

- Skill `caveman` — voz cavernosa ativada por hook
- Skill `caveman-compress` — comprime markdown com pré-processamento determinístico pt-BR (pleonasmos, redundâncias, filler) + passagem pelo LLM
- Skills auxiliares: `caveman-commit`, `caveman-review`, `caveman-help`
- Slash commands: `/caveman`, `/caveman-commit`, `/caveman-review`
- Statusline com indicador de modo

Fork pt-BR de [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman).

## Sobre o Claude Lab

O Claude Lab é o braço de P&D com Claude do Alfredo Gazperi. Plugins publicados aqui nascem de necessidade repetida e amadurecem por calibração contínua com uso real.

## Licença

Cada plugin mantém a licença do seu repositório próprio. Este marketplace em si é MIT.
