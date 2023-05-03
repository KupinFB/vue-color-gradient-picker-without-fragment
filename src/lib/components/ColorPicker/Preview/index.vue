<template>
    <div class="color-preview-area">
        <div class="input-group">
            <RGB
                :red="red"
                :green="green"
                :blue="blue"
                :alpha="alpha"
                :updateColor="updateColor"
            />
        </div>
    </div>
</template>

<script src="./script.js" />
