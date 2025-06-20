# Quote Generator 📝

A simple and elegant web application that displays inspirational quotes with the ability to generate new quotes and share them on X (formerly Twitter).

## 🌟 Features

- **Random Quote Generation**: Get inspirational quotes at the click of a button
- **Author Attribution**: Each quote displays the original author's name
- **Social Sharing**: Share your favorite quotes directly on X (Twitter)
- **Clean UI**: Simple and intuitive user interface

## 🚀 Demo

[Live Demo](https://ahmednasaar.github.io/Quote-Generator/)

## 📸 Screenshots

![Screenshot 2025-06-20 230546](https://github.com/user-attachments/assets/6439ea11-c25b-4beb-a1af-888b62732f79)

![Screenshot 2025-06-20 230704](https://github.com/user-attachments/assets/0314b101-fe41-4578-bab8-b2376eea8560)

## 🛠️ Technologies Used

- **HTML5**: Structure and content
- **CSS3**: Styling and responsive design
- **JavaScript**: API integration and interactivity
- **Quote API**: External API for fetching quotes

## 💡 Usage

1. **Generate Quotes**: Click the "New Quote" button to fetch a random inspirational quote
2. **Share on X**: Click the "Tweet" button to share the current quote on X (Twitter) instantly - it opens a pre-filled tweet window with the quote and author name, no copy-paste needed!
3. **Enjoy**: Read and get inspired by various quotes from different authors

## 📡 API Reference

This project uses the Quotable API to fetch random inspirational quotes. 

**API Endpoint**: `https://api.quotable.io/random`

### API Response Format
```json
{
  "_id": "string",
  "content": "The quotation text",
  "author": "The full name of the author",
  "authorSlug": "The slug of the quote author",
  "length": 42,
  "tags": ["tag1", "tag2", "tag3"]
}
```

## 🙏 Credits & Acknowledgments

- **API Provider**: Special thanks to **Luke Peavey** ([GitHub Profile](https://github.com/lukePeavey)) for creating and maintaining the Quotable API that powers this application
- **Quotes**: All quotes belong to their respective authors

## 🔮 Future Enhancements

- [ ] Add quote categories/tags
- [ ] Implement favorite quotes functionality
- [ ] Add more social sharing options
- [ ] Include quote search feature
- [ ] Add dark/light theme toggle

---

⭐ **If you found this project helpful, please give it a star!** ⭐
