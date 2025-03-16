# 02-create-next-app

1. open vs code
2. based on docs at https://nextjs.org/docs/app/getting-started/installation run
3. npx create-next-app@latest
   app name? nextjs-amazona
4. cd nextjs-amazona
5. npm run dev
6. based on docs at https://ui.shadcn.com/docs/installation/next run
7. npx shadcn@latest init
8. npx shadcn@latest add button
9. copy yellow theme from https://ui.shadcn.com/themes
10. paste it in global.css

    ```css

    ```

11. replace content in main element in page.tsx with

    ```tsx
    import { Button } from '@/components/ui/button'
    ...
    <Button>Button</Button>
    ```

12. publish code to github
13. deploy github repo to vercel
14. go to https://nextjs-amazona.vercel.app
