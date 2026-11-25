# Arabic RTL Form Demo

A small, dependency-free example for designers and developers building Arabic forms that mix right-to-left labels with left-to-right contact details.

Open [the source file](index.html), download it, and open it in a browser. No build step or server is needed. Use fictional details. The form validates locally and does not transmit or store input.

- The page uses RTL layout, the name field follows the entered text, and email and phone stay LTR.
- Phone validation accepts Western, Arabic-Indic, and Eastern Arabic-Indic digits. It checks basic format, not whether the number exists.
- Arabic validation messages are linked to their fields. Submitting invalid values focuses the first invalid field.

### Quick checks

1. Submit an empty form and check that focus moves to the name field.
2. Enter an Arabic name, an invalid email, and a short phone number. Check the Arabic messages.
3. Try محمد علي, demo@example.com, and +٢٠ ١٠٠ ٠٠٠ ٠٠٠٠ for the success state.

## نموذج تسجيل عربي

مثال بسيط لواجهة تسجيل من اليمين لليسار تجمع بين التسميات العربية وحقول البريد الإلكتروني والهاتف من اليسار لليمين. نزّل ملف index.html وافتحه في المتصفح ببيانات وهمية. التحقق محلي والبيانات لا تُرسل ولا تُحفظ.

[MIT License](LICENSE)
