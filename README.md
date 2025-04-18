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

## Errors

### Build Error

	pnpm run build
	> Build error occurred
	[Error: Failed to collect page data for /seed] { type: 'Error' }
	ELIFECYCLE  Command failed with exit code 1.

Solution:

	pnpm approve-builds

### Vercel Deploy Build Error

	[Error: Cannot find module '/vercel/path0/node_modules/.pnpm/bcrypt@5.1.1/node_modules/bcrypt/lib/binding/napi-v3/bcrypt_lib.node'

Solution:

	Replace 'bcrypt' with 'bcryptjs'
