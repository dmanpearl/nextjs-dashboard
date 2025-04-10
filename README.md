## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

# Steps

Using pnpm as package manager instead of npm or yarn

	npm install -g pnpm

tailwind:
- CSS framework like bootstrap, but more custom
- Create Next.js project:

		mkdir nextjs
		cd nextjs
		npx create-next-app@latest nextjs-dashboard --example "https://github.com/vercel/next-learn/tree/main/dashboard/starter-example" --use-pnpm

		Success! Created nextjs-dashboard at /Users/dmanpearl/pixelmonks/nextjs/nextjs-dashboard

		pnpm run dev	# starts server
		pnpm run build	# builds app
		pnpm start		# runs built app

		cd nextjs-dashboard
		pnpm run dev

		pnpm i # or pnpm install
		pnpm dev # start development server

http://localhost:3000

VSCode Copilot: settings > chat.agent.enabled
