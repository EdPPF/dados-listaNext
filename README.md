# Olá Trainees!

Esse repositório contem alguns dados em arquivos `.json` que vocês devem usar para simular a recuperação de dados
de uma base de dados real.

## Como fazer:
Usem o vídeo que fiz (Introdução ao Next) como guia. Lembrem-se que vocês vão usar `fetch()` para acessar esse
repositório usando Server Side Rendering:

```typescript
fetch('https://raw.githubusercontent.com/EdPPF/dados-listaNext/main/...');
```

Os `...` devem ser substituídos pelo arquivo que você quer acessar.

Lembrem também que vocês verificar como os dados estão organizados nesses arquivos para criarem os tipos em TypeScript.

> Obs.: Em cada produto, eu adicionei uma parte que não é requerida nas especificações do projeto final: `ingredientes`.
> Ela será usada aqui para que vocês possam treinar o uso de `.map` para um atributo que é uma lista.
