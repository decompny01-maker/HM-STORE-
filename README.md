# 🛒 HM STORE

A simple, fast, and lightweight e-commerce web application for grocery delivery in 15 minutes.

## Features

✨ **Core Features:**
- 🛍️ Product display with images and prices
- 🛒 Shopping cart with real-time updates
- 👨‍💼 Admin panel to add new products
- 💳 UPI payment integration
- 📦 Quick delivery (15 minutes)

🎯 **Improvements Made:**
- ✅ Remove items from cart
- ✅ Quantity management
- ✅ Cart persistence using localStorage
- ✅ Better UI/UX
- ✅ Input validation
- ✅ Clear cart functionality
- ✅ Responsive design

## How to Use

1. **Open the HTML file** in any modern web browser
2. **View Products** - Browse available grocery items
3. **Add to Cart** - Click "Add" button on any product
4. **Manage Cart** - 
   - Increase/decrease quantities
   - Remove items
   - View total price
5. **Checkout** - Click "Pay via UPI" to complete payment
6. **Admin Panel** - Add new products with name, price, and image URL

## Admin Panel Usage

Fill in the form:
- **Item Name** - Product name (e.g., "Rice")
- **Price** - Product price in ₹ (e.g., "60")
- **Image URL** - Product image link from Unsplash or any CDN
- Click **Add Product** button

## Payment Setup

The default UPI ID is set to `9211617940@paytm`. 

⚠️ **To change:**
1. Open the HTML file
2. Find: `let upiID="9211617940@paytm";`
3. Replace with your UPI ID

## Technical Details

- **Built with:** HTML5, CSS3, JavaScript (Vanilla)
- **No dependencies** - Pure frontend application
- **Browser support:** Chrome, Firefox, Safari, Edge
- **Storage:** Browser localStorage for cart persistence

## Default Products

| Product | Price |
|---------|-------|
| Rice    | ₹60   |
| Milk    | ₹30   |
| Oil     | ₹150  |

## Future Enhancements

- [ ] Database backend
- [ ] User authentication
- [ ] Order history
- [ ] Search/filter products
- [ ] Coupon codes
- [ ] Multiple payment methods
- [ ] Delivery tracking

## License

Open source - Feel free to use and modify!

---

**Made with ❤️ for fast grocery delivery**
