<template>
    <div class="search">
      <span class="material-icons icon-search">search</span>
      <input class="input-search" type="text"/>
      <span class="material-icons-sharp icon-keyboard" data-toggle="tooltip" data-placement="bottom" title="Instrumente pentru introducere de text">keyboard_alt</span>
      <button class="microphone-button" data-toggle="tooltip" data-placement="bottom" title="Efectuati o cautare vocală">
          <img
            class="icon-microphone"
            src="../../assets/microphone.png"
            alt=""
          />
      </button>
    </div>
</template>

<script>
  export default {
      name: 'MainSearch'
  }
</script>

