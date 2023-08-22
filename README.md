<div class="animation-frame">
  <div class="bouncing-animation">
    <p>Hello 👋</p>
    <p>I'm Kirill and I'm an iOS developer.</p>
    <p>Thank you for visiting my GitHub. Welcome!</p>
  </div>
</div>

<style>
.animation-frame {
  background-color: #202020;
  padding:20px;
  border: 0px solid #ccc;
}

.bouncing-animation p {
  font-family: monospace;
  color: white;
  font-size: 22px;
  animation: bounce 1s alternate infinite;
}

@keyframes bounce {
  from {
    transform: translateY(10px);
  }
  to {
    transform: translateY(-10px);
  }
}
</style>
