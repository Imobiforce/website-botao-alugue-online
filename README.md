# Utilização do widget de alugue online

# Botão flutuante

### Credenciais

```js
Solicitar credenciais
```

### Exemplo:

```js
<script src="https://crm.imobiforce.com.br/js/website-integration.js"></script>
<script>

imobiforce({
    'config': {
        Solicitar
        'goal': 'rental', // rental, sale, season
        'preview': 'visit' // proposal, visit, rent-online
    },
    'button': {
        'background-color': '#00AC30',
        'color': 'white',
        'title': 'Faça uma visita',
        'location': 'visit-online'
    },
    'property': {
        'code': 2166,
        'type': 'Casa',
        'url_file': 'https://imobiforce.com.br/wp-content/uploads/2023/05/Logo-mobiforce-CRM-Imobiliario-com-sistema-de-vendas.png',
        'url': 'https://sites.whmsam.com.br/ModelosImobiliarios/imobiforce/detalhes-imovel-locacao.php?id_imovel=767',
        'address': 'ANDRADAS',
        'number': '1294',
        'complement': 'PREDIO',
        'neighborhood': 'CENTRO',
        'city': 'PORTO ALEGRE',
        'state': 'RS',
        'cep': '90020009',
        'rooms': 0,
        'restroom': 1,
        'garages': 0,
        'living_room': 0,
        'private_area': '41',
        'rent': '7000.00',
        'condominium': '50.00',
        'iptu': '10.00',
        'other_values': '100.00',
    },
});

</script>
```



