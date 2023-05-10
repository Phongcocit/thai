<script setup>
    import HomeCard from '../components/HomeCard.vue';
</script>

<template>
    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
            Danh sách phát nhạc
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-center">
            <HomeCard image="https://picsum.photos/id/30/300/300" title="Nhạc trẻ top thịnh hành" subTitle="Subtitle is here" />
            <HomeCard image="https://picsum.photos/id/45/300/300" title="Nhạc theo năm tháng" subTitle="Subtitle is here" />
            <HomeCard class="md:block hidden" image="https://picsum.photos/id/65/300/300" title="Nhạc trữ tình sâu lắng" subTitle="Subtitle is here" />
            <HomeCard class="lg:block hidden" image="https://picsum.photos/id/67/300/300" title="Những ca khúc bất hủ" subTitle="Subtitle is here" />
            <HomeCard class="xl:block hidden" image="https://picsum.photos/id/100/300/300" title="Giai điệu theo từng mùa" subTitle="Subtitle is here" />
        </div>
    </div>

    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
        Radio tiếng nói
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-center">
            <HomeCard image="https://picsum.photos/id/120/300/300" title="Những câu chuyện tình " subTitle="Subtitle is here" />
            <HomeCard image="https://picsum.photos/id/110/300/300" title="Yêu đời hơn mỗi ngày" subTitle="Subtitle is here" />
            <HomeCard class="md:block hidden" image="https://picsum.photos/id/221/300/300" title="Những bài học cuộc sống" subTitle="Subtitle is here" />
            <HomeCard class="lg:block hidden" image="https://picsum.photos/id/232/300/300" title="Đêm khuya thành phố" subTitle="Subtitle is here" />
            <HomeCard class="xl:block hidden" image="https://picsum.photos/id/187/300/300" title="Sâu lắng làng quê nghèo" subTitle="Subtitle is here" />
        </div>
    </div>

    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
        Những ca khúc bất hủ
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-center">
            <HomeCard image="https://picsum.photos/id/88/300/300" title="Nhạc Trịnh" subTitle="Subtitle is here" />
            <HomeCard image="https://picsum.photos/id/243/300/300" title="Nhạc đỏ" subTitle="Subtitle is here" />
            <HomeCard class="md:block hidden" image="https://picsum.photos/id/123/300/300" title="Nhạc vàng" subTitle="Subtitle is here" />
            <HomeCard class="lg:block hidden" image="https://picsum.photos/id/121/300/300" title="Top song ca" subTitle="Subtitle is here" />
            <HomeCard class="xl:block hidden" image="https://picsum.photos/id/99/300/300" title="Bất hủ" subTitle="Subtitle is here" />
        </div>
    </div>
</template>
