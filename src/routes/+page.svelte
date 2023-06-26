
<script>
 

const throwError=()=>{
try {
  abc();
} catch (error) {
  console.error("Error: " + error);
  throw new Error(error)
}
}

</script>

<button on:click={throwError}>Throw Error</button>




