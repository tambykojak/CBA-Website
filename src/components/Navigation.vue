<template>
    <div>
        <nav>
            <img id="logo" src="../assets/logo.png" alt="Circassian Benevolent Association">
            <ul>
                <router-link tag="li" to="/sa"><svg class="icon"><use xlink:href="#house" /></svg><span>Home</span></router-link>
                <router-link tag="li" to="/"><svg class="icon"><use xlink:href="#calendar" /></svg><span>Events</span></router-link>
                <router-link tag="li" to="/"><svg class="icon"><use xlink:href="#group" /></svg><span>Groups</span></router-link>
                <router-link tag="li" to="/"><svg class="icon"><use xlink:href="#v-card" /></svg><span>Members</span></router-link>
                <router-link tag="li" to="/"><svg class="icon"><use xlink:href="#info" /></svg><span>About</span></router-link>
            </ul>
        </nav>
        <svg xmlns="http://www.w3.org/2000/svg" style="display: none;">
            <symbol id="house" viewBox="0 0 20 20">
                <title>Home</title> 
                <desc>An icon for home</desc>
                <path d="M18.672,11H17v6c0,0.445-0.194,1-1,1h-4v-6H8v6H4c-0.806,0-1-0.555-1-1v-6H1.328 c-0.598,0-0.47-0.324-0.06-0.748L9.292,2.22C9.487,2.018,9.743,1.918,10,1.908c0.257,0.01,0.513,0.109,0.708,0.312l8.023,8.031 C19.142,10.676,19.27,11,18.672,11z"/>
            </symbol>

            <symbol id="calendar" viewBox="0 0 20 20">
                <title>Calendar</title> 
                <desc>An icon for Calendar</desc>
                <path d="M17,3h-1v2h-3V3H7v2H4V3H3C1.899,3,1,3.9,1,5v12c0,1.1,0.899,2,2,2h14c1.1,0,2-0.9,2-2V5C19,3.9,18.1,3,17,3 z M17,17H3V9h14V17z M6.5,1h-2v3.5h2V1z M15.5,1h-2v3.5h2V1z"/>
            </symbol>

            <symbol id="info" viewBox="0 0 20 20">
                <title>Info</title> 
                <desc>An icon for Info</desc>
                <path d="M10,0.4c-5.303,0-9.601,4.298-9.601,9.6c0,5.303,4.298,9.601,9.601,9.601c5.301,0,9.6-4.298,9.6-9.601C19.6,4.698,15.301,0.4,10,0.4z M10.896,3.866c0.936,0,1.211,0.543,1.211,1.164c0,0.775-0.62,1.492-1.679,1.492c-0.886,0-1.308-0.445-1.282-1.182C9.146,4.719,9.665,3.866,10.896,3.866z M8.498,15.75c-0.64,0-1.107-0.389-0.66-2.094l0.733-3.025c0.127-0.484,0.148-0.678,0-0.678c-0.191,0-1.022,0.334-1.512,0.664L6.74,10.094c1.555-1.299,3.343-2.061,4.108-2.061c0.64,0,0.746,0.756,0.427,1.92l-0.84,3.18c-0.149,0.562-0.085,0.756,0.064,0.756c0.192,0,0.82-0.232,1.438-0.719l0.362,0.486C10.786,15.168,9.137,15.75,8.498,15.75z"/>
            </symbol>

            <symbol id="v-card" viewBox="0 0 20 20">
                <title>V-card</title> 
                <desc>An icon for V-card</desc>
                <path d="M19,3H1C0.447,3,0,3.447,0,4v12c0,0.552,0.447,1,1,1h18c0.553,0,1-0.448,1-1V4C20,3.448,19.553,3,19,3zM13,7h4v1h-4V7z M11,14.803c-0.129-0.102-0.293-0.201-0.529-0.303c-1.18-0.508-2.961-1.26-2.961-2.176c0-0.551,0.359-0.371,0.518-1.379c0.066-0.418,0.385-0.007,0.445-0.961c0-0.38-0.174-0.475-0.174-0.475s0.088-0.562,0.123-0.996c0.036-0.453-0.221-1.8-1.277-2.097C6.959,6.228,6.834,6.305,7.403,6.004C6.159,5.945,5.869,6.596,5.207,7.075C4.643,7.495,4.49,8.16,4.518,8.514C4.555,8.947,4.643,9.51,4.643,9.51S4.468,9.604,4.468,9.984c0.061,0.954,0.38,0.543,0.445,0.961c0.158,1.008,0.519,0.828,0.519,1.379c0,0.916-1.781,1.668-2.961,2.176C2.268,14.588,2.122,14.673,2,14.76V5h9V14.803z M18,11h-5v-1h5V11z"/>
            </symbol>

            <symbol id="group" viewBox="0 0 20 20">
                <title>Groups</title> 
                <desc>An icon for Groups</desc>
                <path d="M15.989,19.129c0-2.246-2.187-3.389-4.317-4.307c-2.123-0.914-2.801-1.684-2.801-3.334 c0-0.989,0.648-0.667,0.932-2.481c0.12-0.752,0.692-0.012,0.802-1.729c0-0.684-0.313-0.854-0.313-0.854s0.159-1.013,0.221-1.793 c0.064-0.817-0.398-2.56-2.301-3.095C7.88,1.195,7.655,0.654,8.679,0.112c-2.24-0.104-2.761,1.068-3.954,1.93 c-1.015,0.756-1.289,1.953-1.24,2.59c0.065,0.78,0.223,1.793,0.223,1.793s-0.314,0.17-0.314,0.854 c0.11,1.718,0.684,0.977,0.803,1.729C4.481,10.822,5.13,10.5,5.13,11.489c0,1.65-0.212,2.21-2.336,3.124 C0.663,15.53,0,17,0.011,19.129C0.014,19.766,0,20,0,20h16C16,20,15.989,19.766,15.989,19.129z M18.528,13.365 c-1.135-0.457-1.605-1.002-1.605-2.066c0-0.641,0.418-0.432,0.602-1.603c0.077-0.484,0.447-0.008,0.518-1.115 c0-0.441-0.202-0.551-0.202-0.551s0.103-0.656,0.143-1.159c0.05-0.627-0.364-2.247-2.268-2.247c-1.903,0-2.318,1.62-2.269,2.247 c0.042,0.502,0.144,1.159,0.144,1.159s-0.202,0.109-0.202,0.551c0.071,1.107,0.441,0.631,0.518,1.115 c0.184,1.172,0.602,0.963,0.602,1.603c0,1.064-0.438,1.562-1.809,2.152c-0.069,0.029-0.12,0.068-0.183,0.102 c1.64,0.712,4.226,1.941,4.838,4.447H20c0,0,0-1.906,0-2.318C20,14.682,19.727,13.848,18.528,13.365z"/>
            </symbol>
        </svg>
    </div>
</template>

<script>
export default {
}
</script>

<style scoped>
div {
    background-color: whitesmoke;
    color: #5c5c5c;
    width: 100%;
    font-weight: 500;
}
nav {
    display: flex;
    justify-content: space-around;
    border-bottom: 1px solid #e8e8e8;
}
ul {
    display: flex;
    flex-grow: 1;
    flex-basis: 0;
    max-width: 600px;
    list-style-type: none;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
}
li {
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.8rem;
    /* Important: Keeps mobile navigation menu centered */
    width: 100%;
    text-align: center;
}
#logo {
    padding: 1rem;
}
li:hover .icon{
    color:#2ecc71;
    fill:#2ecc71;
}
li:hover {
    color:#2ecc71;
    background-color: white;
    cursor: pointer;
}
.icon {
    display: none;
}

@media only screen and (max-width: 800px) {
    nav {
        display: block;
    }
    ul {
        border-top: 1px solid #e8e8e8;
        max-width: initial;
    }
    li {
        font-size: 1.25rem;
        display: initial;
        padding: 1rem;
    }
    .icon {
        width: 25px;
        height: 25px;
        display: block;
        margin: auto;
        fill: #5c5c5c;
    }
    #logo {
        display: none;
    }
}
</style>
