"# Prisma_pat" 

# project   is  regarding   how  connection  are  made  with setup  the    prisma  
# type  safety

Next, initialize a TypeScript project and add the Prisma CLI as a development dependency to it:

# npm init -y
# npm install prisma typescript tsx @types/node --save-dev

This creates a package.json with an initial setup for your TypeScript app.

Next, set up your Prisma ORM project by creating your Prisma Schema file with the following command:

Next, initialize TypeScript:

# npx tsc --init
============================================================================================================
# npx prisma init

This command does two things:

creates a new directory called prisma that contains a file called schema.prisma, which contains the Prisma schema with your database connection variable and schema models
creates the .env file in the root directory of the project, which is used for defining environment variables (such as your database connection)



