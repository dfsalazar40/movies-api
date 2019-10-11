<template>
    <div>
        <b-card-group deck class="mt-4">
            <movie-card 
            v-for="movie in movies" 
            :key="movie"
            title="{{movie.title}}"
            />
        </b-card-group>       
    </div>
</template>

<script>
import MovieCard from "~/components/movie-card.vue";
//import store from "~/store/index.js"

export default {
    name: 'MoviesList',
//    state: store,
data() {
        return {
            movies: [
                {
                    "popularity": 695.215,
                    "vote_count": 1838,
                    "video": false,
                    "poster_path": "https://wallpapersite.com/images/pages/pic_w/15948.jpg",
                    "id": 475557,
                    "adult": false,
                    "backdrop_path": "https://wallpapersite.com/images/pages/pic_w/15948.jpg",
                    "original_language": "en",
                    "original_title": "Title 1",
                    "genre_ids": [
                    80,
                    18,
                    53
                    ],
                    "title": "Title",
                    "vote_average": 8.7,
                    "overview": "During the 1980s, a failed stand-up comedian is driven insane and turns to a life of crime and chaos in Gotham City while becoming an infamous psychopathic crime figure.",
                    "release_date": "2019-10-04"
                },
                {
                    "popularity": 695.215,
                    "vote_count": 1838,
                    "video": false,
                    "poster_path": "https://wallpapersite.com/images/pages/pic_w/15948.jpg",
                    "id": 475557,
                    "adult": false,
                    "backdrop_path": "https://wallpapersite.com/images/pages/pic_w/15948.jpg",
                    "original_language": "en",
                    "original_title": "Title 2",
                    "genre_ids": [
                    80,
                    18,
                    53
                    ],
                    "title": "Title",
                    "vote_average": 8.7,
                    "overview": "During the 1980s, a failed stand-up comedian is driven insane and turns to a life of crime and chaos in Gotham City while becoming an infamous psychopathic crime figure.",
                    "release_date": "2019-10-04"
                },
                {
                    "popularity": 695.215,
                    "vote_count": 1838,
                    "video": false,
                    "poster_path": "https://wallpapersite.com/images/pages/pic_w/15948.jpg",
                    "id": 475557,
                    "adult": false,
                    "backdrop_path": "https://wallpapersite.com/images/pages/pic_w/15948.jpg",
                    "original_language": "en",
                    "original_title": "Title 3",
                    "genre_ids": [
                    80,
                    18,
                    53
                    ],
                    "title": "Title",
                    "vote_average": 8.7,
                    "overview": "During the 1980s, a failed stand-up comedian is driven insane and turns to a life of crime and chaos in Gotham City while becoming an infamous psychopathic crime figure.",
                    "release_date": "2019-10-04"
                },
                {
                    "popularity": 695.215,
                    "vote_count": 1838,
                    "video": false,
                    "poster_path": "https://wallpapersite.com/images/pages/pic_w/15948.jpg",
                    "id": 475557,
                    "adult": false,
                    "backdrop_path": "https://wallpapersite.com/images/pages/pic_w/15948.jpg",
                    "original_language": "en",
                    "original_title": "Title",
                    "genre_ids": [
                    80,
                    18,
                    53
                    ],
                    "title": "Title",
                    "vote_average": 8.7,
                    "overview": "During the 1980s, a failed stand-up comedian is driven insane and turns to a life of crime and chaos in Gotham City while becoming an infamous psychopathic crime figure.",
                    "release_date": "2019-10-04"
                },
                {
                    "popularity": 695.215,
                    "vote_count": 1838,
                    "video": false,
                    "poster_path": "https://wallpapersite.com/images/pages/pic_w/15948.jpg",
                    "id": 475557,
                    "adult": false,
                    "backdrop_path": "https://wallpapersite.com/images/pages/pic_w/15948.jpg",
                    "original_language": "en",
                    "original_title": "Title",
                    "genre_ids": [
                    80,
                    18,
                    53
                    ],
                    "title": "Title",
                    "vote_average": 8.7,
                    "overview": "During the 1980s, a failed stand-up comedian is driven insane and turns to a life of crime and chaos in Gotham City while becoming an infamous psychopathic crime figure.",
                    "release_date": "2019-10-04"
                },
                {
                    "popularity": 695.215,
                    "vote_count": 1838,
                    "video": false,
                    "poster_path": "https://wallpapersite.com/images/pages/pic_w/15948.jpg",
                    "id": 475557,
                    "adult": false,
                    "backdrop_path": "https://wallpapersite.com/images/pages/pic_w/15948.jpg",
                    "original_language": "en",
                    "original_title": "Title",
                    "genre_ids": [
                    80,
                    18,
                    53
                    ],
                    "title": "Title",
                    "vote_average": 8.7,
                    "overview": "During the 1980s, a failed stand-up comedian is driven insane and turns to a life of crime and chaos in Gotham City while becoming an infamous psychopathic crime figure.",
                    "release_date": "2019-10-04"
                },
                {
                    "popularity": 695.215,
                    "vote_count": 1838,
                    "video": false,
                    "poster_path": "https://wallpapersite.com/images/pages/pic_w/15948.jpg",
                    "id": 475557,
                    "adult": false,
                    "backdrop_path": "https://wallpapersite.com/images/pages/pic_w/15948.jpg",
                    "original_language": "en",
                    "original_title": "Title",
                    "genre_ids": [
                    80,
                    18,
                    53
                    ],
                    "title": "Title",
                    "vote_average": 8.7,
                    "overview": "During the 1980s, a failed stand-up comedian is driven insane and turns to a life of crime and chaos in Gotham City while becoming an infamous psychopathic crime figure.",
                    "release_date": "2019-10-04"
                },
                {
                    "popularity": 695.215,
                    "vote_count": 1838,
                    "video": false,
                    "poster_path": "https://wallpapersite.com/images/pages/pic_w/15948.jpg",
                    "id": 475557,
                    "adult": false,
                    "backdrop_path": "https://wallpapersite.com/images/pages/pic_w/15948.jpg",
                    "original_language": "en",
                    "original_title": "Title",
                    "genre_ids": [
                    80,
                    18,
                    53
                    ],
                    "title": "Title",
                    "vote_average": 8.7,
                    "overview": "During the 1980s, a failed stand-up comedian is driven insane and turns to a life of crime and chaos in Gotham City while becoming an infamous psychopathic crime figure.",
                    "release_date": "2019-10-04"
                },
                {
                    "popularity": 695.215,
                    "vote_count": 1838,
                    "video": false,
                    "poster_path": "https://wallpapersite.com/images/pages/pic_w/15948.jpg",
                    "id": 475557,
                    "adult": false,
                    "backdrop_path": "https://wallpapersite.com/images/pages/pic_w/15948.jpg",
                    "original_language": "en",
                    "original_title": "Title",
                    "genre_ids": [
                    80,
                    18,
                    53
                    ],
                    "title": "Title",
                    "vote_average": 8.7,
                    "overview": "During the 1980s, a failed stand-up comedian is driven insane and turns to a life of crime and chaos in Gotham City while becoming an infamous psychopathic crime figure.",
                    "release_date": "2019-10-04"
                },
                {
                    "popularity": 695.215,
                    "vote_count": 1838,
                    "video": false,
                    "poster_path": "https://wallpapersite.com/images/pages/pic_w/15948.jpg",
                    "id": 475557,
                    "adult": false,
                    "backdrop_path": "https://wallpapersite.com/images/pages/pic_w/15948.jpg",
                    "original_language": "en",
                    "original_title": "Title",
                    "genre_ids": [
                    80,
                    18,
                    53
                    ],
                    "title": "Title",
                    "vote_average": 8.7,
                    "overview": "During the 1980s, a failed stand-up comedian is driven insane and turns to a life of crime and chaos in Gotham City while becoming an infamous psychopathic crime figure.",
                    "release_date": "2019-10-04"
                }
            ]
        }
    },
    components: {
        MovieCard
    }
}
</script>

<style scoped>
    
</style>