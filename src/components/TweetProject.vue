<template>
    <div>
        <button @click="toggleGrid">Grid View</button>
        
            <!-- <p>${"tweets.tweet"}</p>
            <p>{{twitterName}}</p>
            <p>{{twitterDate}}</p> -->
    </div>
</template>

<script>
    export default {
        name : "TweetProject",
        data(){
            return {
                tweets :[
                    {
                        tweet: "Nice one",
                        name: "Dwayne",
                        date: "04 Dec 2022"
                    },
                    {
                        tweet: "Not bad at all",
                        name: "Adam",
                        date: "25 Nov 2022"
                    },
                    {
                        tweet: "Really nice work",
                        name: "Mahi",
                        date: "02 Dec 2022"
                    },
                    {
                        tweet: "That is looking good",
                        name: "Victor",
                        date: "02 Dec 2022"
                    },
                    {
                        tweet: "What does it all mean",
                        name: "Rebecca",
                        date: "22 Nov 2022"
                    },
                    {
                        tweet: "Not to sure about that",
                        name: "Tyler",
                        date: "4 Dec 2022"
                    }
                ]
            }
        },
        methods: {
        },
        mounted () {
            // v-for="(twitter, index) in tweets"
            // :key="index"
            // :tweet="twitter.tweet"
            // :name="twitter.name"
            // :date="twitter.date"

            
        }
        
    }
</script>

<style scoped>

</style>