# CEP e frete da Uninassau

Site em português que consulta o CEP por meio do ViaCEP, localiza o campus da Uninassau por meio do OpenStreetMap e calcula uma estimativa de frete usando distância geográfica e uma tarifa configurável.

## Executar

```bash
npm start
```

Abre `http://localhost:4173` no navegador.

## Testes

```bash
npm test
```

## Importante

- A distância calculada é a distância aérea entre os coordenadas, não a rota real.
- O frete é uma estimativa, não uma cotação oficial do Uber Moto.
- As tarifas são configuráveis na interface.
- A API pública pode apresentar limites de taxa ou indisponibilidade; o site mantém o usuário informado quando isso ocorre.
