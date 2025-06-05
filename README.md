# PDFPro.ai - A Modern Fullstack SaaS Platform

PDFPro.ai is an innovative SaaS platform that allows users to chat with their PDF documents. Built with modern web technologies, it provides an intuitive interface for document interaction and analysis.

![Dashboard Preview](/dashboard-preview.jpg)

## Features

- **PDF Chat Interface**: Have conversations with any PDF document
- **Quick Document Processing**: Upload and start chatting with your documents in seconds
- **User Authentication**: Secure authentication system powered by Kinde Auth
- **Responsive Design**: Beautiful, modern UI that works across devices
- **Real-time Chat**: Interactive chat interface for document queries
- **File Management**: Easy PDF upload and management system
- **Subscription Plans**: Free and Pro tier options available

## Tech Stack

- **Frontend**: 
  - Next.js 13.5
  - React 18
  - TypeScript
  - Tailwind CSS
  - Radix UI Components

- **Backend**: 
  - tRPC
  - Prisma (Database ORM)
  - Pinecone (Vector Database)
  - OpenAI API
  - Uploadthing (File Handling)

- **Authentication**:
  - Kinde Auth

- **Payment Processing**:
  - Stripe

## Getting Started

1. **Clone the repository**

```bash
git clone <repository-url>
cd quill
```

2. **Install dependencies**

```bash
pnpm install
```

3. **Set up environment variables**

Copy the `.env.example` file to `.env` and fill in your environment variables:

```bash
cp .env.example .env
```

4. **Start the development server**

```bash
pnpm run dev
```

5. **Generate Prisma Client**

```bash
pnpm postinstall
```

The application will be available at `http://localhost:3000`

## Project Structure

```
├── src/
│   ├── app/              # Next.js app directory
│   ├── components/       # React components
│   ├── config/          # Configuration files
│   ├── db/              # Database utilities
│   ├── lib/             # Utility functions and services
│   ├── trpc/            # tRPC setup and routes
│   └── types/           # TypeScript type definitions
├── prisma/              # Prisma schema and migrations
├── public/              # Static assets
└── package.json         # Project dependencies
```

## Features in Detail

### 1. Document Chat
- Upload PDF documents
- Process documents for chat functionality
- Real-time chat interface with AI-powered responses

### 2. User Dashboard
- Manage uploaded documents
- View chat history
- Access subscription settings

### 3. Subscription System
- Free tier with basic features
- Pro tier with advanced capabilities
- Stripe integration for payment processing

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
