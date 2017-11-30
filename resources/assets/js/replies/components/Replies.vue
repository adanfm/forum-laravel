<template>
    <div>
        <div class="card">
            <div class="card-content">
                <span class="card-title">Erick {{ replied }}</span>

                <blockquote>
                    Teste
                </blockquote>
            </div>
        </div>
        <div class="card">
            <div class="card-content">
                <span class="card-title">Erick {{ replied }}</span>

                <blockquote>
                    Teste
                </blockquote>
            </div>
        </div>
        <div class="card">
            <div class="card-content">
                <span class="card-title">Erick {{ replied }}</span>

                <blockquote>
                    Teste
                </blockquote>
            </div>
        </div>
        <div class="card grey lighten-4">
            <div class="card-content">
                <span class="card-title">{{ reply }}</span>

                <form action="#">
                    <div class="input-field">
                        <textarea rows="10" class="materialize-textarea" :placeholder="yourAnswer"></textarea>
                    </div>
                    <button class="btn red accent-2" type="submit">{{ send }}</button>
                </form>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        props: [
            'replied',
            'reply',
            'send',
            'yourAnswer'
        ]
    }
</script>
