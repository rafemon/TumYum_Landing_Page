<script>
</script>

<head>
	<script src="https://kit.fontawesome.com/eb06444889.js" crossorigin="anonymous"></script>
</head>
<main>
	<div class="appInformation">
		<img class="appIcon" alt="logo" src="/build/assets/logo_rounded.png">
		<div class="appName">
			<h1>TumYum</h1>
		</div>
		<div class="appDescription">
			<p>tap into your local food scene</p>
		</div>
		<div class="interestForm">
			<a class="typeform" href="https://za1e6wwbj28.typeform.com/to/yy4moyuj"><img class ="betaTestImg" alt="betaSignUp" src="/build/assets/beta-sign-up.png"></a>
		</div>
	</div>
	<div class="footer">
		<section class="social">
			<div class="socialIcons">
				<a href="https://www.instagram.com/tumyumapp/"><i class="fab fa-instagram fa-3x"></i></a>
				<a href="https://discord.gg/QUfFAX9X"><i class="fab fa-discord fa-3x"></i></a>
				<a href="https://www.youtube.com/channel/UCm0tWiLs05bMl0Lv8bkj-bw"><i class="fab fa-youtube fa-3x"></i></a>
			</div>
			<div class="privacyPolicy">
				<a href="https://www.termsfeed.com/live/cd5b92d8-3c69-400f-a9ac-be8020b4be6a">Privacy</a>
			</div>
		</section>
	</div>
</main>

<style>

	.appInformation {
		display: flex;
		flex-direction: column; 
		justify-content: center;
		align-items: center; 
		padding-top: 20%;
		flex-wrap: wrap;
		position: relative;  
	}

	.appInformation::before {
		content: ""; 
		background: linear-gradient(rgba(54, 59, 61, 0.8), rgba(54, 59, 61, 0.8)), url('assets/background.jpg');
		background-repeat: no-repeat;
		background-position: 55% 20%;
		background-size: cover;
		position: absolute; 
		border-radius: 0px 0px 40px 40px; 
		top: 0px; 
		right: 0px; 
		bottom: 0px; 
		left: 0px; 
	}

	.appIcon {
		width: 120px;
		height: 120px;
		position: relative;
	}

	.appName {
		font-family: 'ubie';
		text-align: center;
		color: #C2EB99;
		font-size: 3rem; 
		-webkit-text-stroke: 2px black;
		position: relative;
	}

	.appDescription {
		font-family: 'playfull'; 
		text-align: center;
		color: #ecd3fa;
		font-size: 2rem; 
		position: relative;
	}

	.interestForm {
		display: flex;
		margin-top: 42px;
		height: 20%;
		position: relative;
	}

	.footer {
		padding-top: 100px;
		display: flex; 
		flex-wrap: wrap;
		flex-direction: row;
		justify-content: center; 
		align-content: flex-end;
		position: relative;
	}

	.privacyPolicy {
		text-align: center; 
	}

@font-face {
    font-family: 'ubie';
    src: url('/build/assets/ubie-webfont.woff') format('woff');
	font-weight: 1000;
}	

@font-face {
	font-family: 'playfull';
	src: url('/build/assets/playfull.otf') format('otf');
}

</style>