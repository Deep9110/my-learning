<!-- <div class="text-red-500">Welcomet </div> -->

<div class="flex items-center justify-center h-screen">


<nav class="navmenu absolute translate-y-2/4 p-6 bg-white-500 shadow-lg">
	<!-- <ul class="sticky pl-[50px]  after:content-[''] after:absolute after:w-[2px] after:h-[calc(100% - 58px)] after:left-[36px]
                after:bg-green-500 after:mt-[29px] after:z-[1]"> -->
    <ul class=" pl-[73px] relative">
		<li class="flex flex-col py-4">	
			<a href=" " class="active relative text-lg font-medium text-[#1f1f1f]">Order Confirmed</a>
			<span class="active text-gray-500">Fri, 30th Sep 22</span>
		</li>
		<li class="flex flex-col py-4">
			<!-- <div>
                <div class="">
                    <div class="bg-black w-[6px] h-[6px] rounded">.</div>
                </div>
                <div>
                    <div class="line">-</div>
                </div>
            </div> -->
            <!-- <div> -->
                <a href=" " class="relative text-lg font-medium text-[#1f1f1f]">Shipped</a>
                <span class="text-gray-500">Sat, 1st Ot 22</span>
            <!-- </div> -->
			
			
		</li>
		<li class="flex flex-col py-4">
			
			<a href=" " class="text-lg no-underline relative font-medium text-[#1f1f1f]">Out For Delivery</a>
			<span class="text-gray-500"></span>
		</li>
		<li class="flex flex-col py-4">
			
			<a href=" " class="relative text-lg font-medium text-[#1f1f1f]">Delivery<i class="fa-solid fa-greater-than"></i></a>
            <span class="text-gray-500">Item yet to be delivered.</span>
		</li>
	</ul>
</nav>
</div>


<style>
    .navmenu ul::after{
    content: "";
    position:absolute;
    width: 2px;
    height: calc(100% - 78px);
    left: 36px;
    top: 0;
    background: rgb(118, 196, 118);
    z-index: -1;
    margin-top: 29px;
}   
.navmenu ul li a:before{
    content: '';
    position: absolute;
    background: #fff;
    width:12px;
    height: 12px;
    left: -42px;
    top: 50%;
    transform: translateY(-50%);
    border-radius: 50px;
    border: 3px solid rgb(118, 196, 118);
    transition: background-color 250ms linear;
}

.navmenu ul li a.active{
    font-weight: 600;
}
.navmenu ul li span.active{
    font-weight: 600;
}
.navmenu ul li a.active::before{
    background:green;
}
/* .navmenu ul.active2::after{
    background:green;
} */
.navmenu ul li a.active:before{
    border: 3px solid green;
}
</style>

