<script>
let trekkings = [
    {
        image: './images/pedra_riscada.png',
        title: 'PEDRA RISCADA',
        place: 'Nova Friburgo',
        dates: ['2019-05-11'],
        value: 70,
        level: 'Médio a Pesado',
    },
    {
        image: './images/pedra_riscada.png',
        title: 'CARRANCAS',
        place: 'Minas Gerais',
        dates: ['2019-05-17', '2019-05-18', '2019-05-19'],
        value: 70,
        level: 'Leve',
    },
    {
        image: './images/pedra_riscada.png',
        title: 'TRAVESSIA PETRO x TERE',
        place: 'Petrópolis',
        dates: ['2019-06-09', '2019-06-10'],
        value: 80,
        level: 'Pesado',
    },
    {
        image: './images/pedra_riscada.png',
        title: 'PEDRA DA GÁVEA',
        place: 'Rio de Janeiro',
        dates: ['2019-06-13'],
        value: 100,
        level: 'Pesado',
    },
    {
        image: './images/pedra_riscada.png',
        title: 'PICO DA CALEDÔNIA',
        place: 'Nova Friburgo',
        dates: ['2019-06-20'],
        value: 100,
        level: 'Moderado',
    },
    {
        image: './images/pedra_riscada.png',
        title: 'PICO DA BANDEIRA',
        place: 'Nova Friburgo',
        dates: ['2019-06-20'],
        value: 100,
        level: 'Moderado',
    },
    {
        image: './images/pedra_riscada.png',
        title: 'PERNOITE PEDRA DA TARTARUGA',
        place: 'Teresópolis',
        dates: ['2019-07-20'],
        value: 0,
        level: 'Leve',
    },
    {
        image: './images/pedra_riscada.png',
        title: 'CHAPÉU DA BRUXA x IMPERADOR',
        place: 'Nova Friburgo',
        dates: ['2019-08-11'],
        value: 70,
        level: 'Leve a Moderado',
    },
    {
        image: './images/pedra_riscada.png',
        title: 'PEDRA SELADA',
        place: 'Resende',
        dates: ['2019-08-25'],
        value: 140,
        level: 'Moderado',
    },
    {
        image: './images/pedra_riscada.png',
        title: 'AGULHAS NEGRAS X MORRO DO COUTO',
        place: 'Itatiaia',
        dates: ['2019-09-13', '2019-09-14', '2019-09015'],
        value: 0,
        level: 'Pesado',
    },
    {
        image: './images/pedra_riscada.png',
        title: 'RAFTING',
        place: 'Três Rios',
        dates: ['2019-09-22'],
        value: 0,
        level: undefined,
    },
    {
        image: './images/pedra_riscada.png',
        title: 'PEDRA DO OSSO',
        place: 'Rio de Janeiro',
        dates: ['2019-10-15'],
        value: 90,
        level: 'Moderado',
    },
    {
        image: './images/pedra_riscada.png',
        title: 'PEDRA BRANCA',
        place: 'Rio de Janeiro',
        dates: ['2019-11-10'],
        value: 80,
        level: 'Moderado',
    },
    {
        image: './images/pedra_riscada.png',
        title: 'SÃO TOMÉ DAS LETRAS',
        place: 'Rio de Janeiro',
        dates: ['2019-11-14', '2019-11-15', '2019-11-16', '2019-11-17'],
        value: 0,
    },
    {
        image: './images/pedra_riscada.png',
        title: 'PICO DA TIJUCA + MIRANTE DA CASCATINHA',
        place: 'Rio de Janeiro',
        dates: ['2019-12-08'],
        value: 80,
        level: 'Moderado',
    },
]
</script>

<div>
    {#each trekkings as t, i}
        <section>
            <p>{t.title}</p>
            <img src="{t.image}" alt="{t.title}">
        </section>
    {/each}
</div>

<style>
    section {
	    
    }

    @media(min-width: 768px) {

    }
</style>