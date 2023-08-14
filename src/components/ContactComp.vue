<template>
    <h4>LETS KEEP IN TOUCH</h4>
    <div class="container">
        <form class="form" action="https://formspree.io/f/xdorepzd" method="POST">
            <input placeholder="Enter your name" class="input" type="text" name="name" required>
            <input placeholder="Enter your surname" class="input" type="text" name="name" required>
            <input placeholder="Enter your email" class="input" type="text" name="email" required>
            <textarea placeholder="Leave your feedback or query here..." class="textarea" type="text" name="text" required></textarea>
            <button>Submit</button>
            <button type="reset">Clear</button>
          </form>
    </div>
    <div class="fun">
        <h4 class="h4">Thank you for stopping by ClayExpressions, hope you enjoyed your stay. See you next time!</h4>
        <button class="btn"><a href="../views/HomeView.vue">Back to home page</a></button>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.textarea {
    padding: 10px;
    height: 50%;
    border-radius: 5px;
    background-color: transparent;
    transition: border-color 0.3s ease-in-out, background-color 0.3s ease-in-out, transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
    transform-style: preserve-3d;
    backface-visibility: hidden;
    border: 2px solid white;
    box-shadow: rgba(0, 0, 0, 0.4) 0px 2px 4px, rgba(0, 0, 0, 0.3) 0px 7px 13px -3px, rgba(0, 0, 0, 0.2) 0px -3px 0px inset;
  }

  .h4{
    margin-top: 2rem;
    font-weight: bold;
  }
  
  .textarea::placeholder {
    color: black;
  }
  
  .textarea:hover,
  .textarea:focus {
    border-color: #3b8df2;
    background-color: rgba(255, 255, 255, 0.2);
    transform: scale(0.8) rotateX(-5deg);
    box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.3);
    outline: none;
  }
.container{
    display: flex;
    justify-content: center;
}
.form {
    position: relative;
    width: 100%;
    height: 100vh;
    display: flex;
    flex-direction: column;
    gap: 10px;
    padding: 20px;
    background: white;
    border-radius: 10px;
    overflow: hidden;
    perspective: 1000px;
    transform-style: preserve-3d;
    transform: rotateX(-10deg);
    transition: all 0.3s ease-in-out;
    box-shadow: rgba(0, 0, 0, 0.4) 0px 2px 4px, rgba(0, 0, 0, 0.3) 0px 7px 13px -3px, rgba(0, 0, 0, 0.2) 0px -3px 0px inset;
    animation: form-animation 0.5s ease-in-out;
  }
  
  @keyframes form-animation {
    from {
      transform: rotateX(-30deg);
      opacity: 0;
    }
  
    to {
      transform: rotateX(0deg);
      opacity: 1;
    }
  }
  
  .input {
    padding: 10px;
    height: 10%;
    border-radius: 5px;
    background-color: transparent;
    transition: border-color 0.3s ease-in-out, background-color 0.3s ease-in-out, transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
    transform-style: preserve-3d;
    backface-visibility: hidden;
    border: 2px solid white;
    box-shadow: rgba(0, 0, 0, 0.4) 0px 2px 4px, rgba(0, 0, 0, 0.3) 0px 7px 13px -3px, rgba(0, 0, 0, 0.2) 0px -3px 0px inset;
  }
  
  .input::placeholder {
    color: black;
  }
  
  .input:hover,
  .input:focus {
    border-color: #3b8df2;
    background-color: rgba(255, 255, 255, 0.2);
    transform: scale(0.8) rotateX(-5deg);
    box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.3);
    outline: none;
  }
  
  button {
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    background-color: white;
    color: black;
    font-size: 16px;
    cursor: pointer;
    transform-style: preserve-3d;
    backface-visibility: hidden;
    transform: rotateX(-10deg);
    transition: all 0.3s ease-in-out;
    box-shadow: rgba(0, 0, 0, 0.4) 0px 2px 4px, rgba(0, 0, 0, 0.3) 0px 7px 13px -3px, rgba(0, 0, 0, 0.2) 0px -3px 0px inset;
  }
  
  button:hover {
    background-color: black;
    color: white;
    font-size: 17px;
    transform: scale(0.8) rotateX(20deg);
    box-shadow: rgba(0, 0, 0, 0.4) 0px 2px 4px, rgba(0, 0, 0, 0.3) 0px 7px 13px -3px, rgba(0, 0, 0, 0.2) 0px -3px 0px inset;
  }

  .btn{
        padding: 10px 20px;
        border: none;
        margin-top: 2rem;
        border-radius: 5px;
        background-color: white;
        color: black;
        font-size: 16px;
        cursor: pointer;
        transform-style: preserve-3d;
        backface-visibility: hidden;
        transform: rotateX(-10deg);
        transition: all 0.3s ease-in-out;
        box-shadow: rgba(0, 0, 0, 0.4) 0px 2px 4px, rgba(0, 0, 0, 0.3) 0px 7px 13px -3px, rgba(0, 0, 0, 0.2) 0px -3px 0px inset;
      }
      
      .btn:hover {
        background-color: black;
        color: white;
        font-size: 17px;
        transform: scale(0.8) rotateX(20deg);
        box-shadow: rgba(0, 0, 0, 0.4) 0px 2px 4px, rgba(0, 0, 0, 0.3) 0px 7px 13px -3px, rgba(0, 0, 0, 0.2) 0px -3px 0px inset;
      }

  
</style>