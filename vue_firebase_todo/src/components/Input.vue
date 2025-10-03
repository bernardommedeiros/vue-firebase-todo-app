<template>
  <form>
    <div class="field is-grouped">
      <p class="control is-expanded">
        <input v-model="NewTodoContent"
               class="input"
               type="text" placeholder="Adicione uma atividade"
        >
      </p>
      <p class="control">
        <button
            class="button is-info"
        >
          Adicionar
        </button>
      </p>
    </div>
  </form>
</template>