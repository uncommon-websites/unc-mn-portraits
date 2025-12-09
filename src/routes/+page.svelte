<script lang="ts">
	import { ArrowRight, Check, Zap, Shield, Activity, BarChart3, Globe, Layers } from 'lucide-svelte';
</script>

<div class="min-h-screen bg-gray-50 font-sans text-gray-900 selection:bg-primary-100 selection:text-primary-900">
	<!-- Header -->
	<header class="sticky top-0 z-50 w-full border-b border-gray-200 bg-white/80 backdrop-blur-md">
		<div class="container mx-auto flex h-16 items-center justify-between px-4 md:px-6">
			<div class="flex items-center gap-2">
				<div class="flex h-8 w-8 items-center justify-center rounded-lg bg-primary-600 text-white">
					<Layers class="h-5 w-5" />
				</div>
				<span class="text-xl font-bold tracking-tight">Nexus</span>
			</div>
			<nav class="hidden md:flex items-center gap-8 text-sm font-medium text-gray-600">
				<a href="#features" class="transition-colors hover:text-primary-600">Features</a>
				<a href="#solutions" class="transition-colors hover:text-primary-600">Solutions</a>
				<a href="#pricing" class="transition-colors hover:text-primary-600">Pricing</a>
				<a href="#company" class="transition-colors hover:text-primary-600">Company</a>
			</nav>
			<div class="flex items-center gap-4">
				<a href="#login" class="text-sm font-medium text-gray-600 transition-colors hover:text-gray-900">Log in</a>
				<a href="#signup" class="rounded-full bg-gray-900 px-5 py-2.5 text-sm font-medium text-white transition-all hover:bg-gray-800 hover:shadow-lg hover:shadow-gray-900/20">Sign up</a>
			</div>
		</div>
	</header>

	<main>
		<!-- Hero Section -->
		<section class="relative overflow-hidden pt-20 pb-32 md:pt-32 md:pb-48">
			<div class="absolute inset-0 -z-10 bg-[radial-gradient(ellipse_at_top,_var(--tw-gradient-stops))] from-primary-100/50 via-gray-50 to-gray-50"></div>
			<div class="container mx-auto px-4 text-center md:px-6">
				<div class="animate-fade-in-up mx-auto mb-8 inline-flex items-center rounded-full border border-primary-200 bg-white px-3 py-1 text-sm font-medium text-primary-700 shadow-sm transition-transform hover:scale-105">
					<span class="mr-2 flex h-2 w-2 rounded-full bg-primary-500"></span>
					Introducing Nexus AI 2.0
					<ArrowRight class="ml-2 h-3.5 w-3.5" />
				</div>
				<h1 class="mx-auto max-w-4xl text-5xl font-bold tracking-tight text-gray-900 md:text-7xl lg:text-8xl">
					Scale your workflow <br class="hidden md:block" />
					<span class="text-transparent bg-clip-text bg-gradient-to-r from-primary-600 to-secondary-500">without limits</span>.
				</h1>
				<p class="mx-auto mt-8 max-w-2xl text-lg text-gray-600 md:text-xl leading-relaxed">
					The all-in-one platform for modern engineering teams. Automate your infrastructure, secure your data, and deploy with confidence.
				</p>
				<div class="mt-10 flex flex-col items-center justify-center gap-4 sm:flex-row">
					<a href="#start" class="group inline-flex h-12 items-center justify-center rounded-full bg-primary-600 px-8 text-base font-medium text-white transition-all hover:bg-primary-700 hover:shadow-lg hover:shadow-primary-600/30">
						Start building free
						<ArrowRight class="ml-2 h-4 w-4 transition-transform group-hover:translate-x-1" />
					</a>
					<a href="#demo" class="inline-flex h-12 items-center justify-center rounded-full border border-gray-200 bg-white px-8 text-base font-medium text-gray-900 transition-all hover:border-gray-300 hover:bg-gray-50">
						Request demo
					</a>
				</div>

				<!-- Hero Image / Dashboard Preview -->
				<div class="mx-auto mt-20 max-w-5xl rounded-2xl border border-gray-200 bg-white p-2 shadow-2xl shadow-gray-200/50">
					<div class="aspect-[16/9] overflow-hidden rounded-xl bg-gray-50 border border-gray-100 relative">
						<!-- Mock UI -->
						<div class="absolute inset-0 flex">
							<!-- Sidebar -->
							<div class="w-64 border-r border-gray-200 bg-white p-4 hidden md:block">
								<div class="space-y-4">
									<div class="h-8 w-3/4 rounded bg-gray-100"></div>
									<div class="space-y-2">
										<div class="h-4 w-full rounded bg-gray-50"></div>
										<div class="h-4 w-5/6 rounded bg-gray-50"></div>
										<div class="h-4 w-4/5 rounded bg-gray-50"></div>
									</div>
								</div>
							</div>
							<!-- Main Content -->
							<div class="flex-1 p-6">
								<div class="flex items-center justify-between mb-8">
									<div class="h-8 w-1/3 rounded bg-gray-100"></div>
									<div class="flex gap-2">
										<div class="h-8 w-8 rounded bg-primary-100"></div>
										<div class="h-8 w-24 rounded bg-primary-600"></div>
									</div>
								</div>
								<div class="grid grid-cols-3 gap-6 mb-8">
									<div class="h-32 rounded-xl bg-white border border-gray-100 shadow-sm p-4">
										<div class="h-8 w-8 rounded bg-secondary-100 mb-4"></div>
										<div class="h-4 w-1/2 rounded bg-gray-100"></div>
									</div>
									<div class="h-32 rounded-xl bg-white border border-gray-100 shadow-sm p-4">
										<div class="h-8 w-8 rounded bg-primary-100 mb-4"></div>
										<div class="h-4 w-1/2 rounded bg-gray-100"></div>
									</div>
									<div class="h-32 rounded-xl bg-white border border-gray-100 shadow-sm p-4">
										<div class="h-8 w-8 rounded bg-gray-100 mb-4"></div>
										<div class="h-4 w-1/2 rounded bg-gray-100"></div>
									</div>
								</div>
								<div class="h-64 rounded-xl bg-gray-50 border border-gray-100"></div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</section>

		<!-- Logos -->
		<section class="border-y border-gray-200 bg-white py-12">
			<div class="container mx-auto px-4 md:px-6">
				<p class="mb-8 text-center text-sm font-medium text-gray-500">TRUSTED BY INNOVATIVE TEAMS WORLDWIDE</p>
				<div class="flex flex-wrap justify-center items-center gap-12 opacity-60 grayscale transition-all hover:grayscale-0">
					<!-- Placeholders for logos -->
					<div class="flex items-center gap-2 text-xl font-bold font-display text-gray-900"><div class="h-6 w-6 bg-gray-900 rounded-full"></div>Acme Corp</div>
					<div class="flex items-center gap-2 text-xl font-bold font-display text-gray-900"><div class="h-6 w-6 bg-gray-900 rounded-lg"></div>Global</div>
					<div class="flex items-center gap-2 text-xl font-bold font-display text-gray-900"><div class="h-6 w-6 bg-gray-900 rounded-tr-xl"></div>Sisyphus</div>
					<div class="flex items-center gap-2 text-xl font-bold font-display text-gray-900"><div class="h-6 w-6 bg-gray-900 rounded-full border-2 border-white ring-1 ring-gray-900"></div>Hourglass</div>
					<div class="flex items-center gap-2 text-xl font-bold font-display text-gray-900"><div class="h-6 w-6 bg-gray-900 transform rotate-45"></div>Layers</div>
				</div>
			</div>
		</section>

		<!-- Features Grid -->
		<section id="features" class="py-24 bg-gray-50">
			<div class="container mx-auto px-4 md:px-6">
				<div class="mb-16 text-center">
					<h2 class="mb-4 text-3xl font-bold tracking-tight text-gray-900 md:text-4xl">Everything you need to scale</h2>
					<p class="mx-auto max-w-2xl text-lg text-gray-600">Powerful features designed to help you build, deploy, and manage your applications with ease.</p>
				</div>
				<div class="grid gap-8 md:grid-cols-2 lg:grid-cols-3">
					<!-- Feature 1 -->
					<div class="group rounded-2xl bg-white p-8 shadow-sm transition-all hover:shadow-md hover:-translate-y-1">
						<div class="mb-6 inline-flex h-12 w-12 items-center justify-center rounded-xl bg-primary-50 text-primary-600 group-hover:bg-primary-600 group-hover:text-white transition-colors">
							<Zap class="h-6 w-6" />
						</div>
						<h3 class="mb-3 text-xl font-bold text-gray-900">Lightning Fast</h3>
						<p class="text-gray-600 leading-relaxed">Optimized for speed with edge caching and global CDNs. Your users will never wait.</p>
					</div>
					<!-- Feature 2 -->
					<div class="group rounded-2xl bg-white p-8 shadow-sm transition-all hover:shadow-md hover:-translate-y-1">
						<div class="mb-6 inline-flex h-12 w-12 items-center justify-center rounded-xl bg-primary-50 text-primary-600 group-hover:bg-primary-600 group-hover:text-white transition-colors">
							<Shield class="h-6 w-6" />
						</div>
						<h3 class="mb-3 text-xl font-bold text-gray-900">Enterprise Security</h3>
						<p class="text-gray-600 leading-relaxed">Bank-grade encryption, SOC2 compliance, and automated threat detection built-in.</p>
					</div>
					<!-- Feature 3 -->
					<div class="group rounded-2xl bg-white p-8 shadow-sm transition-all hover:shadow-md hover:-translate-y-1">
						<div class="mb-6 inline-flex h-12 w-12 items-center justify-center rounded-xl bg-primary-50 text-primary-600 group-hover:bg-primary-600 group-hover:text-white transition-colors">
							<Activity class="h-6 w-6" />
						</div>
						<h3 class="mb-3 text-xl font-bold text-gray-900">Real-time Analytics</h3>
						<p class="text-gray-600 leading-relaxed">Gain deep insights into your application performance and user behavior instantly.</p>
					</div>
					<!-- Feature 4 -->
					<div class="group rounded-2xl bg-white p-8 shadow-sm transition-all hover:shadow-md hover:-translate-y-1">
						<div class="mb-6 inline-flex h-12 w-12 items-center justify-center rounded-xl bg-primary-50 text-primary-600 group-hover:bg-primary-600 group-hover:text-white transition-colors">
							<BarChart3 class="h-6 w-6" />
						</div>
						<h3 class="mb-3 text-xl font-bold text-gray-900">Custom Reports</h3>
						<p class="text-gray-600 leading-relaxed">Create custom dashboards and reports to track the metrics that matter most to you.</p>
					</div>
					<!-- Feature 5 -->
					<div class="group rounded-2xl bg-white p-8 shadow-sm transition-all hover:shadow-md hover:-translate-y-1">
						<div class="mb-6 inline-flex h-12 w-12 items-center justify-center rounded-xl bg-primary-50 text-primary-600 group-hover:bg-primary-600 group-hover:text-white transition-colors">
							<Globe class="h-6 w-6" />
						</div>
						<h3 class="mb-3 text-xl font-bold text-gray-900">Global Infrastructure</h3>
						<p class="text-gray-600 leading-relaxed">Deploy to 35+ regions worldwide with a single click. Low latency for everyone.</p>
					</div>
					<!-- Feature 6 -->
					<div class="group rounded-2xl bg-white p-8 shadow-sm transition-all hover:shadow-md hover:-translate-y-1">
						<div class="mb-6 inline-flex h-12 w-12 items-center justify-center rounded-xl bg-primary-50 text-primary-600 group-hover:bg-primary-600 group-hover:text-white transition-colors">
							<Layers class="h-6 w-6" />
						</div>
						<h3 class="mb-3 text-xl font-bold text-gray-900">Seamless Integration</h3>
						<p class="text-gray-600 leading-relaxed">Connect with your favorite tools like GitHub, Slack, and Jira in seconds.</p>
					</div>
				</div>
			</div>
		</section>

		<!-- Pricing Section -->
		<section id="pricing" class="py-24 bg-white border-t border-gray-200">
			<div class="container mx-auto px-4 md:px-6">
				<div class="mb-16 text-center">
					<h2 class="mb-4 text-3xl font-bold tracking-tight text-gray-900 md:text-4xl">Simple, transparent pricing</h2>
					<p class="mx-auto max-w-2xl text-lg text-gray-600">Choose the plan that's right for you. No hidden fees.</p>
				</div>
				<div class="grid gap-8 md:grid-cols-3 max-w-6xl mx-auto">
					<!-- Basic Plan -->
					<div class="rounded-2xl border border-gray-200 bg-white p-8 shadow-sm hover:border-gray-300 transition-colors">
						<h3 class="text-lg font-semibold text-gray-900">Starter</h3>
						<div class="mt-4 flex items-baseline text-gray-900">
							<span class="text-4xl font-bold tracking-tight">$0</span>
							<span class="ml-1 text-xl font-semibold text-gray-500">/mo</span>
						</div>
						<p class="mt-4 text-sm text-gray-500">Perfect for side projects and learning.</p>
						<ul class="mt-6 space-y-4">
							<li class="flex items-start">
								<Check class="mr-3 h-5 w-5 flex-shrink-0 text-primary-600" />
								<span class="text-sm text-gray-600">Up to 3 projects</span>
							</li>
							<li class="flex items-start">
								<Check class="mr-3 h-5 w-5 flex-shrink-0 text-primary-600" />
								<span class="text-sm text-gray-600">Community support</span>
							</li>
							<li class="flex items-start">
								<Check class="mr-3 h-5 w-5 flex-shrink-0 text-primary-600" />
								<span class="text-sm text-gray-600">1GB storage</span>
							</li>
						</ul>
						<a href="#" class="mt-8 block w-full rounded-lg bg-gray-50 px-4 py-3 text-center text-sm font-semibold text-gray-900 hover:bg-gray-100 transition-colors">Get Started</a>
					</div>

					<!-- Pro Plan -->
					<div class="relative rounded-2xl border border-primary-200 bg-white p-8 shadow-xl shadow-primary-900/5">
						<div class="absolute -top-4 left-1/2 -translate-x-1/2 rounded-full bg-primary-600 px-3 py-1 text-xs font-medium text-white">Most Popular</div>
						<h3 class="text-lg font-semibold text-gray-900">Pro</h3>
						<div class="mt-4 flex items-baseline text-gray-900">
							<span class="text-4xl font-bold tracking-tight">$29</span>
							<span class="ml-1 text-xl font-semibold text-gray-500">/mo</span>
						</div>
						<p class="mt-4 text-sm text-gray-500">For growing teams and startups.</p>
						<ul class="mt-6 space-y-4">
							<li class="flex items-start">
								<Check class="mr-3 h-5 w-5 flex-shrink-0 text-primary-600" />
								<span class="text-sm text-gray-600">Unlimited projects</span>
							</li>
							<li class="flex items-start">
								<Check class="mr-3 h-5 w-5 flex-shrink-0 text-primary-600" />
								<span class="text-sm text-gray-600">Priority support</span>
							</li>
							<li class="flex items-start">
								<Check class="mr-3 h-5 w-5 flex-shrink-0 text-primary-600" />
								<span class="text-sm text-gray-600">10GB storage</span>
							</li>
							<li class="flex items-start">
								<Check class="mr-3 h-5 w-5 flex-shrink-0 text-primary-600" />
								<span class="text-sm text-gray-600">Advanced analytics</span>
							</li>
						</ul>
						<a href="#" class="mt-8 block w-full rounded-lg bg-primary-600 px-4 py-3 text-center text-sm font-semibold text-white hover:bg-primary-700 transition-colors shadow-lg shadow-primary-600/20">Start Free Trial</a>
					</div>

					<!-- Enterprise Plan -->
					<div class="rounded-2xl border border-gray-200 bg-white p-8 shadow-sm hover:border-gray-300 transition-colors">
						<h3 class="text-lg font-semibold text-gray-900">Enterprise</h3>
						<div class="mt-4 flex items-baseline text-gray-900">
							<span class="text-4xl font-bold tracking-tight">$99</span>
							<span class="ml-1 text-xl font-semibold text-gray-500">/mo</span>
						</div>
						<p class="mt-4 text-sm text-gray-500">For large organizations with custom needs.</p>
						<ul class="mt-6 space-y-4">
							<li class="flex items-start">
								<Check class="mr-3 h-5 w-5 flex-shrink-0 text-primary-600" />
								<span class="text-sm text-gray-600">Unlimited everything</span>
							</li>
							<li class="flex items-start">
								<Check class="mr-3 h-5 w-5 flex-shrink-0 text-primary-600" />
								<span class="text-sm text-gray-600">24/7 dedicated support</span>
							</li>
							<li class="flex items-start">
								<Check class="mr-3 h-5 w-5 flex-shrink-0 text-primary-600" />
								<span class="text-sm text-gray-600">SSO & Audit logs</span>
							</li>
							<li class="flex items-start">
								<Check class="mr-3 h-5 w-5 flex-shrink-0 text-primary-600" />
								<span class="text-sm text-gray-600">Custom contracts</span>
							</li>
						</ul>
						<a href="#" class="mt-8 block w-full rounded-lg bg-gray-50 px-4 py-3 text-center text-sm font-semibold text-gray-900 hover:bg-gray-100 transition-colors">Contact Sales</a>
					</div>
				</div>
			</div>
		</section>

		<!-- Footer -->
		<footer class="bg-white border-t border-gray-200 py-12">
			<div class="container mx-auto px-4 md:px-6">
				<div class="grid gap-8 md:grid-cols-4">
					<div class="col-span-1 md:col-span-1">
						<div class="flex items-center gap-2 mb-4">
							<div class="flex h-6 w-6 items-center justify-center rounded bg-primary-600 text-white">
								<Layers class="h-4 w-4" />
							</div>
							<span class="text-lg font-bold">Nexus</span>
						</div>
						<p class="text-sm text-gray-500">Making the world a better place through constructing elegant hierarchies.</p>
					</div>
					<div>
						<h4 class="font-semibold text-gray-900 mb-4">Product</h4>
						<ul class="space-y-2 text-sm text-gray-600">
							<li><a href="#" class="hover:text-primary-600">Features</a></li>
							<li><a href="#" class="hover:text-primary-600">Integrations</a></li>
							<li><a href="#" class="hover:text-primary-600">Pricing</a></li>
							<li><a href="#" class="hover:text-primary-600">Changelog</a></li>
						</ul>
					</div>
					<div>
						<h4 class="font-semibold text-gray-900 mb-4">Company</h4>
						<ul class="space-y-2 text-sm text-gray-600">
							<li><a href="#" class="hover:text-primary-600">About</a></li>
							<li><a href="#" class="hover:text-primary-600">Blog</a></li>
							<li><a href="#" class="hover:text-primary-600">Careers</a></li>
							<li><a href="#" class="hover:text-primary-600">Contact</a></li>
						</ul>
					</div>
					<div>
						<h4 class="font-semibold text-gray-900 mb-4">Legal</h4>
						<ul class="space-y-2 text-sm text-gray-600">
							<li><a href="#" class="hover:text-primary-600">Privacy</a></li>
							<li><a href="#" class="hover:text-primary-600">Terms</a></li>
							<li><a href="#" class="hover:text-primary-600">Cookie Policy</a></li>
						</ul>
					</div>
				</div>
				<div class="mt-12 border-t border-gray-200 pt-8 text-center text-sm text-gray-500">
					© 2024 Nexus Inc. All rights reserved.
				</div>
			</div>
		</footer>
	</main>
</div>

