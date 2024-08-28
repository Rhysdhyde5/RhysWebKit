<script>
    import Navbar from '../components/Navbar.svelte';
  </script>
  
  <Navbar />
  
  <slot />

  <div class="background">
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
 </div>
  
  <style>
     @keyframes move {
    100% {
        transform: translate3d(0, 0, 1px) rotate(360deg);
    }
}

.background {
    position: fixed;
    width: 100vw;
    height: 100vh;
    top: 0;
    left: 0;
    background: #141118;
    overflow: hidden;
    z-index: -1;
}

.background span {
    width: 20vmin;
    height: 20vmin;
    border-radius: 20vmin;
    backface-visibility: hidden;
    position: absolute;
    animation: move;
    animation-duration: 45;
    animation-timing-function: linear;
    animation-iteration-count: infinite;
}


.background span:nth-child(0) {
    color: #3d76b3;
    top: 99%;
    left: 73%;
    animation-duration: 55s;
    animation-delay: -2s;
    transform-origin: 16vw -8vh;
    box-shadow: -40vmin 0 5.509419215446355vmin currentColor;
}
.background span:nth-child(1) {
    color: #3c867d;
    top: 8%;
    left: 13%;
    animation-duration: 49s;
    animation-delay: -25s;
    transform-origin: -11vw 1vh;
    box-shadow: 40vmin 0 5.657450488366031vmin currentColor;
}
.background span:nth-child(2) {
    color: #3c867d;
    top: 26%;
    left: 10%;
    animation-duration: 34s;
    animation-delay: -33s;
    transform-origin: -9vw -21vh;
    box-shadow: 40vmin 0 5.2847707323917135vmin currentColor;
}
.background span:nth-child(3) {
    color: #3d76b3;
    top: 85%;
    left: 39%;
    animation-duration: 39s;
    animation-delay: -31s;
    transform-origin: 8vw -14vh;
    box-shadow: -40vmin 0 5.854302916506819vmin currentColor;
}
.background span:nth-child(4) {
    color: #3d76b3;
    top: 3%;
    left: 54%;
    animation-duration: 47s;
    animation-delay: -9s;
    transform-origin: 10vw 7vh;
    box-shadow: -40vmin 0 5.744327983880025vmin currentColor;
}
.background span:nth-child(5) {
    color: #3d76b3;
    top: 60%;
    left: 20%;
    animation-duration: 48s;
    animation-delay: -37s;
    transform-origin: 1vw -23vh;
    box-shadow: -40vmin 0 5.684615630043944vmin currentColor;
}
.background span:nth-child(6) {
    color: #3c867d;
    top: 57%;
    left: 27%;
    animation-duration: 26s;
    animation-delay: -42s;
    transform-origin: -17vw 14vh;
    box-shadow: 40vmin 0 5.645796758181673vmin currentColor;
}
.background span:nth-child(7) {
    color: #adebff;
    top: 58%;
    left: 31%;
    animation-duration: 32s;
    animation-delay: -27s;
    transform-origin: 0vw 2vh;
    box-shadow: 40vmin 0 5.390130711103919vmin currentColor;
}
.background span:nth-child(8) {
    color: #adebff;
    top: 100%;
    left: 23%;
    animation-duration: 18s;
    animation-delay: -11s;
    transform-origin: 9vw 7vh;
    box-shadow: 40vmin 0 5.884841911486578vmin currentColor;
}
.background span:nth-child(9) {
    color: #3d76b3;
    top: 2%;
    left: 84%;
    animation-duration: 37s;
    animation-delay: -24s;
    transform-origin: 14vw 23vh;
    box-shadow: 40vmin 0 5.4762655854801vmin currentColor;
}
.background span:nth-child(10) {
    color: #3c867d;
    top: 98%;
    left: 36%;
    animation-duration: 12s;
    animation-delay: -34s;
    transform-origin: -8vw 14vh;
    box-shadow: -40vmin 0 5.460473286198827vmin currentColor;
}
.background span:nth-child(11) {
    color: #3c867d;
    top: 92%;
    left: 99%;
    animation-duration: 25s;
    animation-delay: -28s;
    transform-origin: -17vw -22vh;
    box-shadow: 40vmin 0 5.905157661162068vmin currentColor;
}
.background span:nth-child(12) {
    color: #3c867d;
    top: 31%;
    left: 88%;
    animation-duration: 23s;
    animation-delay: -46s;
    transform-origin: 7vw -2vh;
    box-shadow: 40vmin 0 5.783516419704593vmin currentColor;
}
.background span:nth-child(13) {
    color: #3c867d;
    top: 93%;
    left: 98%;
    animation-duration: 36s;
    animation-delay: -2s;
    transform-origin: 19vw -1vh;
    box-shadow: 40vmin 0 5.5725498153716595vmin currentColor;
}
.background span:nth-child(14) {
    color: #3c867d;
    top: 69%;
    left: 55%;
    animation-duration: 14s;
    animation-delay: -36s;
    transform-origin: -12vw 12vh;
    box-shadow: -40vmin 0 5.899681224573236vmin currentColor;
}
.background span:nth-child(15) {
    color: #3d76b3;
    top: 39%;
    left: 4%;
    animation-duration: 27s;
    animation-delay: -28s;
    transform-origin: 15vw 13vh;
    box-shadow: -40vmin 0 5.5091422249414vmin currentColor;
}
.background span:nth-child(16) {
    color: #3c867d;
    top: 59%;
    left: 16%;
    animation-duration: 22s;
    animation-delay: -50s;
    transform-origin: -5vw -1vh;
    box-shadow: -40vmin 0 5.761004551362643vmin currentColor;
}
.background span:nth-child(17) {
    color: #3d76b3;
    top: 38%;
    left: 40%;
    animation-duration: 48s;
    animation-delay: -27s;
    transform-origin: -13vw -15vh;
    box-shadow: 40vmin 0 5.804488870936517vmin currentColor;
}
.background span:nth-child(18) {
    color: #3d76b3;
    top: 50%;
    left: 4%;
    animation-duration: 22s;
    animation-delay: -11s;
    transform-origin: -18vw -12vh;
    box-shadow: 40vmin 0 5.697613695063721vmin currentColor;
}
.background span:nth-child(19) {
    color: #adebff;
    top: 69%;
    left: 45%;
    animation-duration: 24s;
    animation-delay: -18s;
    transform-origin: -4vw -9vh;
    box-shadow: 40vmin 0 5.066541817452778vmin currentColor;
}
  </style>