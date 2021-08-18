<template>
    <a class="nav-link-round" target="_blank" v-on:click="showModal">
            <img class="user-avatar" src="../../assets/avatar-3.png" alt="" />
    </a>
    <div id="myModal" class="modal">
        <div class="modal-content">
            <img src="../../assets/avatar-content.png" class="modal-img">
        </div>
    </div>
</template>

<script>
    window.onclick = function(event) {
        if (event.target == document.getElementById("myModal")) {
            document.getElementById("myModal").style.display = "none";
        }
    }

    export default {
        name: 'NavAvatar',
        methods: {
            showModal: function (){
                var modal = document.getElementById("myModal");
                modal.style.display = "block";
            }
        }
    }
    
</script>