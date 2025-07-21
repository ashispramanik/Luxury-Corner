# Luxury-Corner

A premium house website showcasing luxury real estate properties with elegant design and seamless user experience.

## 🏡 About

Luxury-Corner is a sophisticated web platform designed to showcase premium residential properties. The website combines modern web technologies with elegant design to provide an immersive experience for luxury home buyers and real estate enthusiasts.

## ✨ Features

- **Property Showcase**: High-quality image galleries and virtual tours
- **Advanced Search**: Filter properties by location, price, size, and amenities
- **Interactive Maps**: Explore properties with integrated mapping
- **Responsive Design**: Optimized for all devices and screen sizes
- **Contact Management**: Seamless inquiry and contact system
- **Admin Dashboard**: Easy content management for property listings

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager
- Modern web browser

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/luxury-corner.git
cd luxury-corner
```

2. Install dependencies
```bash
npm install
```

3. Set up environment variables
```bash
cp .env.example .env.local
```
Edit `.env.local` with your configuration:
```
NEXT_PUBLIC_API_URL=your_api_url
GOOGLE_MAPS_API_KEY=your_maps_api_key
DATABASE_URL=your_database_url
```

4. Run the development server
```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## 🛠️ Built With

- **Frontend**: React.js / Next.js
- **Styling**: Tailwind CSS / Styled Components
- **Database**: PostgreSQL / MongoDB
- **Authentication**: NextAuth.js
- **Image Optimization**: Next.js Image Optimization
- **Maps**: Google Maps API
- **Deployment**: Vercel / Netlify

## 📁 Project Structure

```
luxury-corner/
├── public/
│   ├── images/
│   └── favicon.ico
├── src/
│   ├── components/
│   │   ├── common/
│   │   ├── property/
│   │   └── layout/
│   ├── pages/
│   ├── styles/
│   ├── utils/
│   └── hooks/
├── docs/
├── package.json
└── README.md
```

## 🎨 Key Components

- **PropertyCard**: Individual property display component
- **SearchFilter**: Advanced property filtering system
- **ImageGallery**: Property image carousel and lightbox
- **ContactForm**: Lead generation and inquiry forms
- **MapView**: Interactive property location mapping

## 📱 Responsive Breakpoints

- Mobile: 320px - 768px
- Tablet: 768px - 1024px
- Desktop: 1024px+

## 🔧 Development

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint
- `npm run test` - Run test suite

### Code Style

This project uses:
- ESLint for code linting
- Prettier for code formatting
- Husky for pre-commit hooks

## 🌐 Deployment

### Production Build

```bash
npm run build
npm run start
```

### Environment Variables

Required environment variables for production:
- `DATABASE_URL`
- `NEXTAUTH_SECRET`
- `GOOGLE_MAPS_API_KEY`
- `CLOUDINARY_URL` (for image uploads)

## 📄 API Documentation

### Property Endpoints

- `GET /api/properties` - Get all properties
- `GET /api/properties/:id` - Get single property
- `POST /api/properties` - Create new property (admin)
- `PUT /api/properties/:id` - Update property (admin)
- `DELETE /api/properties/:id` - Delete property (admin)

### Search Endpoints

- `GET /api/search` - Search properties with filters
- `GET /api/locations` - Get available locations

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## 📞 Contact

Email: ashispramanik2002@gmail.com 

## 🙏 Acknowledgments

- Design inspiration from luxury real estate platforms
- Icons from Lucide React
- Images from Unsplash (replace with actual sources)

---

**Luxury-Corner** - *Where elegance meets technology*
