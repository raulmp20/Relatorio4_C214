<script>
    import "animate.css";

    export let acao;

</script>

<style>
  .botao-custom {
    padding: 10px 20px;
    background-color: #007bff;
    color: #fff;
    border: none;
    cursor: pointer;
  }

  .botao-custom:hover {
    animation: heartBeat 1s infinite; 
  }
</style>

<div>
  <button on:click={acao} class="botao-custom">Marcar GOL</button>
</div>
