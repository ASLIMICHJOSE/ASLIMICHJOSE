<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8" />
	<meta name="viewport" content="width=device-width, initial-scale=1.0" />
	<title>Arun Hari | GitHub Profile</title>
	<style>
		:root {
			--bg: #030712;
			--fg: #e8f0ff;
			--accent: #00ffc6;
			--muted: #9fb3c8;
			--card: #0b1020;
			--border: #1c2335;
			--glow: 0 0 16px rgba(0, 255, 198, 0.4);
			--font: "Fira Code", "JetBrains Mono", Consolas, "SFMono-Regular", "Source Code Pro", Menlo, monospace;
		}

		* {
			box-sizing: border-box;
		}

		body {
			margin: 0;
			padding: 32px 16px 64px;
			background: radial-gradient(circle at 20% 20%, rgba(0, 255, 198, 0.08), transparent 35%),
					radial-gradient(circle at 80% 10%, rgba(0, 255, 198, 0.06), transparent 40%),
					radial-gradient(circle at 50% 80%, rgba(0, 255, 198, 0.05), transparent 45%),
									var(--bg);
			color: var(--fg);
			font-family: var(--font);
			line-height: 1.6;
			min-height: 100vh;
			display: flex;
			justify-content: center;
		}

		main {
			width: min(1040px, 100%);
			background: linear-gradient(145deg, rgba(255, 255, 255, 0.02), rgba(0, 0, 0, 0.25));
			border: 1px solid var(--border);
			border-radius: 18px;
			padding: 32px 24px 40px;
			box-shadow: 0 24px 80px rgba(0, 0, 0, 0.35), inset 0 0 0 1px rgba(255, 255, 255, 0.02);
		}

		h1, h2, h3 {
			text-align: center;
			margin: 8px 0 12px;
			letter-spacing: 0.5px;
		}

		h1 {
			font-size: clamp(26px, 5vw, 34px);
		}

		h2 {
			font-size: clamp(18px, 3.5vw, 22px);
			color: var(--accent);
			text-transform: uppercase;
			letter-spacing: 1.4px;
		}

		p {
			margin: 0 0 10px;
			text-align: center;
			color: var(--muted);
		}

		.divider {
			margin: 28px auto;
			width: 82%;
			height: 1px;
			background: linear-gradient(90deg, transparent, rgba(0, 255, 65, 0.6), transparent);
			box-shadow: var(--glow);
		}

		.card {
			background: var(--card);
			border: 1px solid var(--border);
			border-radius: 14px;
			padding: 18px 16px 16px;
			margin: 18px 0;
			box-shadow: 0 12px 32px rgba(0, 0, 0, 0.35);
		}

		.list {
			margin: 0;
			padding: 0;
			list-style: none;
			display: grid;
			gap: 10px;
			justify-content: center;
		}

		.list li {
			color: var(--fg);
			text-align: center;
		}

		.badges img, .icons img {
			filter: drop-shadow(0 0 10px rgba(0, 255, 65, 0.35));
		}

		.footer-wave {
			margin-top: 32px;
			text-align: center;
		}

		.section-title {
			margin-top: 12px;
		}

		@media (max-width: 600px) {
			body {
				padding: 20px 10px 48px;
			}

			.list {
				gap: 8px;
			}
		}
	</style>
</head>
<body>
	<main>
		<h1>Hey there, I'm Arun Hari 👋</h1>

		<p>
			<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=950&color=00FFC6&center=true&vCenter=true&width=540&lines=Frontend+Developer+%26+Intern;React+enthusiast+%7C+JS+craftsman;Learning+by+shipping+daily;Pixel-perfect+meets+performant" alt="Typing animation" />
		</p>

		<p class="badges">
			<img src="https://komarev.com/ghpvc/?username=Arunhari67980&label=Views+so+far&color=00ffc6&style=flat" alt="Profile views counter" />
		</p>

		<p>
			<img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg" alt="Contribution snake animation" />
		</p>

		<div class="divider"></div>

		<section class="card">
			<h2 class="section-title">About Me</h2>
			<ul class="list">
				<li>🎓 BE Computer Science Engineering undergrad from Kanyakumari, India</li>
				<li>🧭 Building for the web with curiosity and caffeine</li>
				<li>📌 Intern + learner who prefers demos over decks</li>
			</ul>
			<ul class="list" style="margin-top:12px;">
				<li>🛠️ Daily drivers: <strong>HTML</strong>, <strong>CSS</strong>, <strong>JavaScript</strong></li>
				<li>⚛️ Leveling up in <strong>React</strong>, <strong>Node.js</strong>, and <strong>Tailwind</strong></li>
				<li>😄 Fun fact: I rename variables more than I rename files</li>
			</ul>
		</section>

		<p>
			<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark" alt="Animated quote" />
		</p>

		<div class="divider"></div>

		<section class="card">
			<h2 class="section-title">Highlights</h2>
			<ul class="list">
				<li>🚀 Shipped responsive UIs that stay fast on low-end devices</li>
				<li>⚛️ Built modular React components with reuse in mind</li>
				<li>🎨 Obsessed with spacing scales, contrast, and readable type</li>
				<li>🧠 Experimenting with design systems + Tailwind tokens</li>
				<li>🤝 Collaborative intern experience with agile rituals</li>
				<li>📈 Commit streak fueled by curiosity and side projects</li>
			</ul>
		</section>

		<section class="card">
			<h2 class="section-title">Currently Learning</h2>
			<ul class="list">
				<li>⚛️ React performance tricks: memoization, suspense basics</li>
				<li>🎨 Tailwind theming + design tokens</li>
				<li>🌐 API choreography with fetch/axios + optimistic UIs</li>
				<li>🧪 Component testing with Jest + Storybook stories</li>
			</ul>
		</section>

		<section class="card">
			<h2 class="section-title">Building Right Now</h2>
			<ul class="list">
				<li>🗺️ A minimal travel notes PWA with offline-first caching</li>
				<li>📊 A dashboard micro-ui exploring charts with plain SVG</li>
				<li>🧭 Refactoring personal portfolio to ship faster on mobile</li>
			</ul>
		</section>

		<section class="card">
			<h2 class="section-title">Tech Stack</h2>
			<p class="icons">
				<img src="https://skillicons.dev/icons?i=html,css,js,react,nodejs,git,github,vscode&theme=dark" alt="Tech stack icons" />
			</p>
		</section>

		<section class="card">
			<h2 class="section-title">GitHub Trophies</h2>
			<p>
				<img src="https://github-profile-trophy.vercel.app/?username=Arunhari67980&theme=matrix&no-frame=true&row=1&column=7" alt="GitHub trophies" />
			</p>
		</section>

		<section class="card">
			<h2 class="section-title">Connect With Me</h2>
			<p>
				<a href="https://www.linkedin.com/in/arunhari678" aria-label="LinkedIn">
					<img src="https://skillicons.dev/icons?i=linkedin" height="42" alt="LinkedIn" />
				</a>
				&nbsp;&nbsp;&nbsp;&nbsp;
				<a href="mailto:arunhari67890@gmail.com" aria-label="Email">
					<img src="https://skillicons.dev/icons?i=gmail" height="42" alt="Gmail" />
				</a>
			</p>
		</section>

		<div class="divider"></div>

		<p class="footer-wave">
			<img src="https://capsule-render.vercel.app/api?type=waving&color=00FF41&height=100&section=footer" alt="Footer wave" />
		</p>

		<p style="text-align:center; margin-top:6px; color:var(--accent); font-weight:700;">Always learning. Always building.</p>
	</main>
</body>
</html>
