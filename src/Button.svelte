<button on:click>
<slot />
</button>

<style>
 button{
    font: inherit;
    padding: 0.15rem 0.5rem;
    background: #d40202d5;
    border: 1px solid #d40202d5;
    color: white;
    cursor: pointer;
  }

  button:hover,
  button:active {
    box-shadow: 1px 1px 6px rgba(0, 0, 0, 0.26);
  }
</style>