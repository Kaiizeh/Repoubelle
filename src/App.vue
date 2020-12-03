<template>
  <div class="card row position-relative d-flex">
    <img src="https://via.placeholder.com/416x300" style="" />
    <a
      class="modal-maWindow"
      href="https://via.placeholder.com/416x300"
      target="blank"
    >
      <svg
        width="5em"
        height="5em"
        viewBox="0 0 16 16"
        class="bi bi-zoom-in"
        fill="#f1f1f1"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          fill-rule="evenodd"
          d="M6.5 12a5.5 5.5 0 1 0 0-11 5.5 5.5 0 0 0 0 11zM13 6.5a6.5 6.5 0 1 1-13 0 6.5 6.5 0 0 1 13 0z"
        />
        <path
          d="M10.344 11.742c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1 6.538 6.538 0 0 1-1.398 1.4z"
        />
        <path
          fill-rule="evenodd"
          d="M6.5 3a.5.5 0 0 1 .5.5V6h2.5a.5.5 0 0 1 0 1H7v2.5a.5.5 0 0 1-1 0V7H3.5a.5.5 0 0 1 0-1H6V3.5a.5.5 0 0 1 .5-.5z"
        />
      </svg>
    </a>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
img {
  width: 416px;
  height: 300px;
}
.modal-maWindow {
  position: absolute;
  color: #f1f1f1;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 416px;
  height: 300px;
  background-color: black;
  opacity: 0;
  transition: 0.2s;
}

.modal-maWindow:hover {
  opacity: 0.7;
}
</style>
