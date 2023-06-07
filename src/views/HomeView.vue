<script setup>
    import HomeCard from '../components/HomeCard.vue';
</script>

<template>
    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
            Recently Played
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-center">
            <HomeCard class="w-[16rem]" image="http://127.0.0.1:5175/images/albumCovers/DiariesOfAHero.png" title="Diaries Of A Hero" subTitle="By Fola" />
            <!-- <HomeCard image="https://picsum.photos/id/45/300/300" title="Title is here" subTitle="Subtitle is here" /> -->
            <!-- <HomeCard class="md:block hidden" image="http://127.0.0.1:5175/images/albumCovers/DiariesOfAHero.png" title="Diaries Of A Hero" subTitle="By Fola" /> -->
            <!-- <HomeCard class="lg:block hidden" image="https://picsum.photos/id/67/300/300" title="Title is here" subTitle="Subtitle is here" /> -->
            <!-- <HomeCard class="xl:block hidden" image="https://picsum.photos/id/100/300/300" title="Title is here" subTitle="Subtitle is here" /> -->
        </div>
    </div>

    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
        Made For Fola
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-center">
            <HomeCard image="https://picsum.photos/id/120/300/300" title="Six Mix" subTitle="Adele, The Chainsmokers and MileyCyrus" />
            <HomeCard image="https://dailymix-images.scdn.co/v2/img/ab6761610000e5eb11de9e26d17433c5d960c15f/1/en/default" title="Daily Mix 1" subTitle="Nathaniel Bassey, Mercy Chinwo, Phil Thompson" />
            <HomeCard class="md:block hidden" image="https://dailymix-images.scdn.co/v2/img/ab6761610000e5eb9d41ef5854614a584f1881b0/2/en/default" title="Daily Mix 2" subTitle="EmotionKontrolla, Marizu and more" />
            <HomeCard class="lg:block hidden" image="https://dailymix-images.scdn.co/v2/img/ab6761610000e5eb575acae2a628b8e68e90a23b/3/en/default" title="Daily Mix 3" subTitle="ElevationWorship, Maverick City Music, Bethel Music" />
            <HomeCard class="xl:block hidden" image="https://picsum.photos/id/187/300/300" title="Moses Bliss Mix" subTitle="Minister GUC, Yadah and Uche Agu" />
        </div>
    </div>

    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
        Recommended radio
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-center">
            <HomeCard image="https://seeded-session-images.scdn.co/v1/img/artist/1WDoaSGtFrO4ZPMZqLiaEU/en" title="Tope Alabi Radio" subTitle="By Spotify" />
            <HomeCard image="https://seeded-session-images.scdn.co/v1/img/artist/68ra9ISZg5HZYwKaPtKvMp/en" title="Mercy Chinwo Radio" subTitle="By Spotify" />
            <HomeCard class="md:block hidden" image="https://seeded-session-images.scdn.co/v1/img/artist/01zeOIPQPPmHKytrc9sPC3/en" title="Pv Idemudia Radio" subTitle="By Spotify" />
            <HomeCard class="lg:block hidden" image="https://seeded-session-images.scdn.co/v1/img/artist/79MTG7HPurBgQ0ilwJ4AgM/en" title="Moses Bliss Radio" subTitle="By Spotify" />
            <HomeCard class="xl:block hidden" image="https://seeded-session-images.scdn.co/v1/img/artist/5WUlDfRSoLAfcVSX1WnrxN/en" title="Sia Radio" subTitle="By Spotify" />
        </div>
    </div>
</template>
