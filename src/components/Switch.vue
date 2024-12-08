<template>
  <div class="switch-container">
    <button
      :class="{ active: isActive === 'builders' }"
      class="builders"
      @click="setActive('builders')"
    >
      <p>Для строителей</p>
    </button>
    <button
      class="architects"
      :class="{ active: isActive === 'architects' }"
      @click="setActive('architects')"
    >
      <p>Для архитекторов</p>
    </button>
  </div>
</template>

<script setup>
import { ref } from "vue";

// Local state for managing the active switch
const isActive = ref("builders");

// Define the emit function
const emit = defineEmits(["isActive"]);

// Function to set the active button and emit the change
const setActive = (value) => {
  isActive.value = value;
  emit("isActive", value); // Emit the event with the selected value
};
</script>

<style lang="scss" scoped>
.switch-container {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 20px auto;
  overflow: hidden;
}

button {
  flex: 1;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 16px 30px;
  border-bottom: 1px solid var(--red);
  border-left: 1px solid var(--red);
  border-top: 1px solid var(--red);

  max-width: 575px;
  width: 100%;
  transition: background-color 0.3s ease, color 0.3s ease;
  font-size: 1.25rem;
  letter-spacing: 0;
  font-weight: 700;
  font-style: normal;
  text-decoration: none;
  margin-bottom: 39px;
  & p {
    font-size: 1.25rem;
    letter-spacing: 0;
    font-weight: 700;
    font-style: normal;
    text-decoration: none;
    white-space: nowrap;
  }
}

.builders {
  border-radius: 4px 0 0 4px;
}
.architects {
  border-radius: 0 4px 4px 0;
}
button.active {
  background-color: var(--red);
  color: white;
}

button:not(.active) {
  background-color: white;
  color: #d0021b;
  border: 1px solid #d0021b;
}

button:not(.active):hover {
  background: rgba(214, 18, 41, 0.05);
}
</style>
