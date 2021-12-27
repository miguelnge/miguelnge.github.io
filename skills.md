---
title: Skills
layout: page
description:
image: assets/images/tile_skills.jpg
nav-menu: true
style: style2
---

<!-- Main -->
<div id="main" class="alt">

<!-- One -->
<section id="one">
	<div class="inner">

<!-- Technical skills -->
<div>
    <h2>Technical skills</h2>
	<!-- Area 1 -->
	<button class="collapsible">Area1</button>
	<div class="collapsible-content">
  		<div class="skillset">
			<div class="skillset-item">
				<h5 class="skillset-level-title">Solution1</h5>
				<div class="skillset-level-bar">
					<div class="skillset-level-bar-inner" data-level="98%" style="width: 98%;"></div>
				</div>
			</div>
			<div class="skillset-item">
				<h5 class="skillset-level-title">Solution2</h5>
				<div class="skillset-level-bar">
					<div class="skillset-level-bar-inner" data-level="98%" style="width: 98%;"></div>
				</div>
			</div>
		</div>
	</div>
</div>

<hr class="major">

<!-- Professional skills -->
<div>
    <h2>Professional skills</h2>
</div>

<hr class="major">

<!-- Languages -->
<div>
    <h2>Languages</h2>
</div>

</div>
</section>

</div>

<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.maxHeight){
      content.style.maxHeight = null;
    } else {
      content.style.maxHeight = content.scrollHeight + "px";
    } 
  });
}
</script>