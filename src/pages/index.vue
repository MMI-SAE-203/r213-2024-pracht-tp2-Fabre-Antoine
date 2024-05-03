<script setup lang="ts">
import type { MaisonRecord } from '@/types'
import MaisonCard from '@/components/MaisonCard.vue';
const maisonsListe:MaisonRecord[] = 
[
  {
    "adresse": "12 Rue des Chênes, 75000 Paris",
    "collectionId": "6x4i96kn4mu6a1x",
    "collectionName": "maison",
    "created": "2024-05-02 06:35:09.377Z",
    "favori": true,
    "id": "gum4oxart2njbfb",
    "image": "e4a5129a_2cef_11e2_9486_6533ad266c57_493x328_yVhqGnlsGn.webp",
    "nbChambres": 4,
    "nbSdb": 2,
    "nomMaison": "La Rose Rouge",
    "prix": 350000,
    "surface": 200,
    "updated": "2024-05-02 07:27:42.404Z"
  },
  {
    "adresse": "8 Chemin du Pin Parasol, 44000 Nantes",
    "collectionId": "6x4i96kn4mu6a1x",
    "collectionName": "maison",
    "created": "2024-05-02 06:36:42.809Z",
    "favori": false,
    "id": "dyimrz04waxvfgk",
    "image": "sans_titre_6_1_eZoejIjxw0.jpg",
    "nbChambres": 5,
    "nbSdb": 3,
    "nomMaison": "Soleil Levant",
    "prix": 600000,
    "surface": 300,
    "updated": "2024-05-02 06:36:42.809Z"
  },
  {
    "adresse": "25 Rue des Iris, 69000 Lyon",
    "collectionId": "6x4i96kn4mu6a1x",
    "collectionName": "maison",
    "created": "2024-05-02 06:38:06.122Z",
    "favori": true,
    "id": "jqg8fr0kdapty7w",
    "image": "maison_contemporaine_lyon_et_69_7Pbs6Se6jO.jpg",
    "nbChambres": 3,
    "nbSdb": 2,
    "nomMaison": "Bleu Horizon",
    "prix": 450000,
    "surface": 220,
    "updated": "2024-05-02 07:27:38.215Z"
  },
  {
    "adresse": "18 Chemin des Sapins, 73000 Chambéry",
    "collectionId": "6x4i96kn4mu6a1x",
    "collectionName": "maison",
    "created": "2024-05-02 06:40:20.030Z",
    "favori": false,
    "id": "a3fd6ra1q4o2h36",
    "image": "i_bac1e8c4c3f2f7253d8031f478b121f7_z9pdvPiK07.jpg",
    "nbChambres": 6,
    "nbSdb": 4,
    "nomMaison": "Montagne Éternelle",
    "prix": 700000,
    "surface": 400,
    "updated": "2024-05-02 06:41:28.506Z"
  },
  {
    "adresse": "5 Rue des Lilas, 31000 Toulouse",
    "collectionId": "6x4i96kn4mu6a1x",
    "collectionName": "maison",
    "created": "2024-05-02 06:48:38.414Z",
    "favori": true,
    "id": "jf6pmmc0xn4jy3b",
    "image": "t_l_chargement_7lux4SKIFL.jpg",
    "nbChambres": 2,
    "nbSdb": 1,
    "nomMaison": "L'Échappée Belle",
    "prix": 250000,
    "surface": 120,
    "updated": "2024-05-02 07:27:32.784Z"
  }
]

</script>

<template>
  <div>
    <MaisonCard v-bind="maisonsListe[0]" />
    
  <h1 class="text-2xl">Bonjour monde !</h1>
</div>
</template>