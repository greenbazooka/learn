<style>
body {
   background-color: #ffffff;
}
.flex-container {
   display: -webkit-flex;
   display: flex;
   justify-content: space-around;
   align-items: flex-start;
   flex-wrap: wrap;
   width: 100%;
   height: 100%;
   background-color: #ffffff;
}
.flex-item {
   width: 154px;
   height: 100%;
   margin: 10px;
   text-align: center;
}
.flex-item h2 {
   padding-top: 5px;
   transition: 0.3s;
}
.learnpageIcons {
   box-sizing: border-box;
   width: 100%;
   height: 150px;
   border: 4px solid #ffffff;
   display: table;
   background-color: #44b3e2;
   color: #ffffff;
   box-shadow: none;
   transition: 0.3s ease-in-out;
}
.fcontainer {
   -webkit-tap-highlight-color: rgba(255, 255, 255, 0);
   -webkit-touch-callout: none;
   -webkit-user-select: none;
   -khtml-user-select: none;
   -moz-user-select: none;
   -ms-user-select: none;
    user-select: none;
}
.fcontainer:hover .learnpageIcons {
   background-color: #777777;
   /*border: 8px solid #ffffff;*/
}
.fcontainer:hover h2 {
   color: #777777;
}
.learnpageIcons i {
   display: table-cell;
   vertical-align: middle;
   text-align: center;
   text-shadow: none;
}
.nextPrev {
   display: none;
}
.editGit {
   display: none;
}
.learnDesc {
  position: relative;
  margin: 0 auto;
  padding: 5px 10px 5px 10px;
  width: 400px;
  background-color: #368fb4;
  margin-bottom: 15px;
  box-shadow: 1px 2px 10px #888;
}
.learnDesc-desc {
  display: inline-block;
}
.learnDesc-desc p {
  width: 300px;
  color: #ffffff;
}
.learnDesc-desc a {
  font-weight: bold;
  color: #fff !important;
}
.learnDesc-book  {
  width: 100px;
  display: inline-block;
}
@media (max-width: 562px) {
  .learnDesc {
    width: 50%;
  }
  .learnDesc-desc p {
    width: 100%;
  }
  .learnDesc-book  {
    width: 100%;
  }
  .learnDesc-book img {
    display: block;
    margin: 0 auto;
  }
}
</style>
<div class="learnDesc">
				<div class="learnDesc-book">
				  <img src="http://localhost/learn/theme/book.png" style="width:80px; padding:10px">
				</div><div class="learnDesc-desc">
					<p>
					  An in-depth look at the basic principles of electricity
					  monitoring, sustainable energy and more.<br>
					  Information specific to setting-up, installing and configuring an OpenEnergyMonitor system is available in the <a href="https://guide.openenergymonitor.org">Guide</a>.
					</p>
				</div>
			</div>
<div class="flex-container">
	<div class="flex-item">
    <div class="fcontainer">
      <a href="electricity-monitoring/ac-power-theory/introduction">
      	<div class='learnpageIcons'>
      		<div class='iconCircle'></div>
      	</div>
      	<h2>Electricity Monitoring</h2>
      	<p>Learn all about the basics of electricity monitoring, from AC power theory to designing and building your own monitoring system.</p>
    	</a>
    </div>
	</div>
	<div class="flex-item">
	  <div class="fcontainer">
	    <a href="sustainable-energy/energy/introduction">
		    <div class='learnpageIcons'>
		    	<div class='iconCircle'></div>
		    </div>
		    <h2>Sustainable Energy</h2>
		    <p>Exploring the context of energy, renewable supply, energy efficiency and zero carbon energy systems.</p>
		  </a>
		</div>
	</div>
	<div class="flex-item">
	  <div class="fcontainer">
	    <a href="pv-diversion/introduction/choosing-an-energy-diverter.md">
		    <div class='learnpageIcons'>
			    <div class='iconCircle'></div>
		    </div>
		    <h2>PV<br>Diversion</h2>
		    <p>Learn how to build a solar PV diverter to make use of excess energy.</p>
		  </a>
	  </div>
	</div>
</div>
<script>
  $(".learnpageIcons:eq(0)").append(
  "<i class='fa fa-bolt fa-3x'></i>");
  $(".learnpageIcons:eq(1)").append(
  "<i class='fa fa-globe fa-3x'></i>");
  $(".learnpageIcons:eq(2)").append(
  "<i class='fa fa-random fa-3x' style='padding:8px 0 0 4px;'></i>");
</script>
