# Next.js Boilerplate with NextAuth, Prisma, and Tailwind CSS

This is a boilerplate project for building a Next.js application with NextAuth, Prisma, and Tailwind CSS. It provides a starting point for building authenticated applications

## Features

- NextAuth for authentication and authorization
- Prisma for database access and management
- Tailwind CSS for styling
- PNPM for package management

## Getting Started

1.  Clone the repository:

```bash
git clone https://github.com/safarrr/nextwithnextauth.git
```

2.  Clone the repository:

```bash
cd nextwithnextauth
```

3.  Install the dependencies using PNPM:

> if you want to use npm please [read this](https://stackoverflow.com/questions/72293946/revert-from-pnpm-to-npm)

```bash
pnpm install
```

3.  Rename the .env.example file to .env.

4.  Run the database migrations

```bash
pnpm prisma migrate dev --name init
```

6. Start the development server

```bash
pnpm dev
```

## Configuration

- NextAuth: You can configure authentication providers and options in the `src/lib/auth.ts` file.

## Learn More

To learn more about the tools and technologies used in this boilerplate, please refer to their official documentation:

[Next.js Documentation](https://nextjs.org/docs)

[NextAuth Documentation](https://next-auth.js.org/getting-started/introduction)

[Prisma Documentation](https://www.prisma.io/docs)

[Tailwind CSS Documentation](https://tailwindcss.com/docs)

[pnpm Documentation](https://pnpm.io)
