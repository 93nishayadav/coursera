body{
	padding-left:30px;
	}
	
	*{
		box-sizing: border-box;
      }
	
	h1{
	     text-align: center;
		margin-top: 40px;
		font-family: cursive;
	}
	
	h2
	{
		float:right;
        background-color: yellow;
		border: 1px solid black;
        margin-bottom:0;
        margin-top:0;
	}
	 
	p{
      color: chocolate;
      width:90%;
      height:170px;
      font-family: cursive;
      margin-right:auto;
      margin-left: auto; 
      padding-top: 20px;
     
    }
    
    div{
    	position: relative;
    	background-color: grey;
    	border:1px solid black;
    	margin-bottom: 10px;
    	margin-right: 10px;
    	overflow:hidden;
    }
    
	/*-------------large devices only--------------*/
	@media (min-width: 992px){
     .col-lg-1,.col-lg-2,.col-lg-3,.col-lg-4,.col-lg-5,.col-lg-6,.col-lg-7,.col-lg-8,.col-lg-9,.col-lg-10,.col-lg-11,.col-lg-12{
     	float:left;
     	border:1px solid black;
     }
    
     .col-lg-4{
     	width:32%;
     }
     
	}
	/*-------------medium devices only-------------*/
	@media (min-width:768px) and (max-width:991px){
		.col-md-1,.col-md-2,.col-md-3,.col-md-4,.col-md-5,.col-md-6,.col-md-7,.col-md-8,.col-md-9,.col-md-10,.col-md-11,.col-md-12{
			float:left;
			border:1px solid black;
			
		}
		.col-md-6{
			width:48%;

		}
		
		.col-md-12{
			width:97.5%;
		}
	}
	
	/*-------------small devices only---------------*/
	@media(max-width: 767px){
		.col-sm-12{
			border:1px solid black;
			float:left;
			width:100%;
		}
	}
