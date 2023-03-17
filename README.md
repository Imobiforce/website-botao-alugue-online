# Utilização do widget de alugue online

# Botão flutuante

### Credenciais

```js
var userId: Solicitar
var companyId: Solicitar
```

### Exemplo:

```js
<script src="https://crm.imobiforce.com.br/js/website-integration.js"></script>
<script>

imobiforce({
    'config': {
        'company_id': companyId,
        'user_id': userId,
        'goal': 'rental', // rental, sale, season
        'preview': 'proposal' // proposal, visit, rent-online
    },
    'button': {
        'background-color': '#00AC30',
        'color': 'white',
        'title': 'Alugue online',
        'location': 'alugue-online' // id do elemento
    },
    'property': {
        'code': 2165,
        'type': 'Casa',
        'url': 'https://mount.samisistemas.com.br/vendas/Foto_115_282002_1.jpg',
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



