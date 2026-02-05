# Skin Care Earth Day Discount

Professional email template promoting a Skin Care Earth Day Discount for Retail and Consumer Goods industries.

![Thumbnail](./thumbnail.png)

## Template Details

- **Industries:** Retail, Consumer Goods
- **Message Type:** Marketing
- **Tags:** promotion, discount, skin care, earth day

## Files
- `index.html`: The improved, localized, and branded HTML template.
- `template.blade.php`: Ready-to-use Laravel Blade template with `asset()` helpers.
- `assets/`: Directory containing localized images and styles used in the template.

## Usage in Laravel

### 1. Store the Template
Place the `index.html` content in a Blade view (e.g., `resources/views/emails/skin-care-earth-day-discount.blade.php`).

### 2. Handle Assets
Move the content of `assets/` to your public directory (e.g., `public/vendor/mail-templates/skin-care-earth-day-discount/`) and update the paths in the HTML to use the `asset()` helper.

### 3. Send Email
```php
Mail::to($user)->send(new \App\Mail\GenericEmail([
    'view' => 'emails.skin-care-earth-day-discount',
    'data' => [
        // Your dynamic data here
    ]
]));
```

---
*Created with ❤️ by **[LaravelMail.com](https://laravelmail.com)** - Your source for professional email templates.*
