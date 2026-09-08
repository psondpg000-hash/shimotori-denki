<script>
	import './company.css';
</script>


<svelte:head>
	<title>会社概要｜株式会社シモトリ電気｜新潟県妙高市の電気工事</title>

	<meta
		name="description"
		content="株式会社シモトリ電気の会社概要をご紹介します。所在地、代表者、建設業許可番号、業務内容などの会社情報をご確認いただけます。新潟県妙高市を中心に電気工事を承っています。"
	/>
	<script type="application/ld+json">
		{JSON.stringify({
			"@context": "https://schema.org",
			"@type": "Electrician",
			"name": "株式会社シモトリ電気",
			"url": "https://example.com",
			"telephone": "0255-82-3670",
			"address": {
				"@type": "PostalAddress",
				"addressRegion": "新潟県",
				"addressLocality": "妙高市",
				"streetAddress": "大字関山4864"
			}
		})}
	</script>
</svelte:head>

<!-- ページタイトル -->

<section class="company-page-title">
	<div class="company-container">

		<nav class="company-breadcrumb" aria-label="パンくずリスト">
			<a href="/">Home</a>
			<span>/</span>
			<span>会社概要</span>
		</nav>

		<h1>Profile</h1>
		<p>会社概要</p>

	</div>
</section>


<!-- 会社概要 -->

<section class="company-info">
	<div class="company-container">

		<div class="company-card">

			<div class="company-item">
				<div class="company-label">
					会社名
				</div>

				<div class="company-content">
					株式会社シモトリ電気
				</div>
			</div>


			<div class="company-item">
				<div class="company-label">
					代表者
				</div>

				<div class="company-content">
					霜鳥　正弘（シモトリ　マサヒロ）
				</div>
			</div>


			<div class="company-item">
				<div class="company-label">
					所在地
				</div>

				<div class="company-content">
					〒949-2235<br />
					新潟県妙高市大字関山4864
				</div>
			</div>


			<div class="company-item">
				<div class="company-label">
					電話番号
				</div>

				<div class="company-content">
					<a href="tel:09012345678">
						0255-82-3670
					</a>
				</div>
			</div>


			<div class="company-item">
				<div class="company-label">
					資本金
				</div>

				<div class="company-content">
					10,000千円
				</div>
			</div>


			<div class="company-item">
				<div class="company-label">
					建設業許可番号
				</div>

				<div class="company-content">
					新潟県知事許可　第046859号
				</div>
			</div>


			<div class="company-item">
				<div class="company-label">
					業務内容
				</div>

				<div class="company-content">
					<ul>
						<li>住宅電気工事</li>
						<li>店舗・事務所電気工事</li>
						<li>LED照明工事</li>
						<li>エアコン取付</li>
					</ul>
				</div>
			</div>

		</div>

	</div>
</section>


<!-- アクセス -->

<section class="company-access">
	<div class="company-container">

		<h2 class="company-access-title">
			Access
		</h2>

		<div class="company-map">
			<iframe
				src="https://www.google.com/maps?q=株式会社シモトリ電気新潟県妙高市関山４８６４&output=embed"
				loading="lazy"
				allowfullscreen
				title="会社所在地"
			></iframe>
		</div>

	</div>
</section>