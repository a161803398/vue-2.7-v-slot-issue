<template>
  <div>
    <slot :user="Math.random() > 0.5 ? { name: 'test' } : undefined"></slot>
  </div>
</template>
