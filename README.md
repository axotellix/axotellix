
# Welcome!

### Top projects.
<div align="left" width="100%" background="Orange">
	<h5>FIT | Fitness center</h5>
	<svg xmlns="http://www.w3.org/2000/svg" width="320" height="200" fill="#ebedf0" class="bi bi-plus" viewBox="0 0 320 200"
	  style="background: #474661; border-radius: 4px; cursor: pointer; transition: background 0.25s"
	>
	  <!-- [ styles ] -->
	  <style>
	    .modal, .modal-text {
	      opacity: 0;
	      transition: opacity 0.25s;
	    }
	    .cover {
	      display: block;
	      width: 100%; height: 100%;
	      position: absolute;
	      left: 0; top: 0;
	      z-index: 999;
	      fill: Black;
	      fill-opacity: 0.7;
	      z-index: -1;
	    }
	    .logo {
	      transition: opacity 0.25s;
	    }
	  </style>
	  <!-- [ content ] -->
	  <svg class = 'logo' width="100%" height="100%" viewBox="-7 -7 30 30">
	      <path
		  d="M8 4a.5.5 0 0 1 .5.5v3h3a.5.5 0 0 1 0 1h-3v3a.5.5 0 0 1-1 0v-3h-3a.5.5 0 0 1 0-1h3v-3A.5.5 0 0 1 8 4z"
	      />
	  </svg>
	  <svg class = 'modal' width="100%" height="100%" viewBox="-7 -7 30 30"
	     onMouseOver="
		this.style.opacity='1';
		document.querySelector('.logo').style.opacity='0.5'
		document.querySelector('.modal-text').style.opacity='1';
	     "
	     onMouseOut="
		this.style.opacity='0';
		document.querySelector('.logo').style.opacity='1'
		document.querySelector('.modal-text').style.opacity='0';
	     "
	   >
	     <rect
		 width="100%"
		 height="100%"
		 x="0"
		 y="0"
		 class="cover"
	      >
	      <rect/>
	  </svg>
	  <svg class = 'modal-text' width="100%" height="100%" viewBox="-7 -7 30 30">
	    <text 
		 font-family="Arial"
		 font-size="17" 
		 fill="#ebedf0"
		 x="50%" y="50%"
		 dominant-baseline="middle"
		 text-anchor="middle"
	     >
	       FIT | Fitness center
	     </text>
	  </svg>
	</svg>

</div> 


