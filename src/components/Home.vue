<template>
    <div style = "text-align: center;">
        <h1>Welcome to IE Bank</h1>
        <img src = "@/assets/logo.png" alt="IE Bank Logo" style="max-width: 300px; margin-top: 20px;" />
        <br>
        <button @click="GoToAccounts">Go to Dashboard</button>
    </div>
</template>

<script>

import router from '@/router';

export default {
  methods: {
    GoToAccounts() {
      router.push('/accounts');
    }
  }
};
</script>