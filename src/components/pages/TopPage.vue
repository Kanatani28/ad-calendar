<template>
    <div class="has-text-white">
        <section class="hero is-primary is-fullheight">
            <div class="hero-body">
                <div class="container">
                    <h1 class="title is-size-1">
                        アドベントカレンダーツクール
                    </h1>
                    <h2 class="subtitle">
                        さあ、みんなでアウトプットをはじめよう
                    </h2>
                    <div class="content is-size-4">
                        <p>クリスマスまでの期間に日数を数えるために使用されるアドベントカレンダー。<br>
                        最近ではQiitaやブログなどの記事を投稿していくイベントを指す言葉としても有名ですよね。<br>
                        そんなアドベントカレンダーをいつでも、気軽に作れるようにしてみました。
                        </p>
                    </div>
                    <router-link class="button is-primary is-outlined is-inverted" to="/new-calendar" exact>さっそくカレンダーを作ってみる</router-link>
                </div>
            </div>
            <Footer class="hero-foot" />
        </section>
    </div>
</template>

<script>
import Footer from '@/components/globals/Footer'

export default {
    components: {
        Footer,
    },
}
</script>

<style scoped>

</style>>