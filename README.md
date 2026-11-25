# DukaanDost
Dukaan Dost – A Voice-First Business Assistant for Small Shopkeepers
# Build a Working Prototype of Dukaan Dost – A Voice-First Business Assistant for India

Build a mobile-first, AI-powered voice assistant called **Dukaan Dost**, designed for small shopkeepers, kirana store owners, street vendors, and local retailers across India.

## 1. Target Users

The target users are small business owners in villages, towns, and cities who may have limited digital literacy and find typing or complicated accounting applications difficult. They speak Hindi, English, Telugu, Tamil, Bengali, Marathi, Kannada, Malayalam, and other regional Indian languages. They may also mix languages while speaking, such as Hinglish or Telugu-English. The app must understand different regional accents and speaking styles.

## 2. Voice Flow – Step by Step

**Step 1: Welcome and Language Selection**

When users open the app, Dukaan Dost says: "Namaste! Welcome to Dukaan Dost. Aap apni dukaan ka hisaab sirf bolkar manage kar sakte hain. Which language would you prefer?"

Allow users to select or speak their preferred language.

**Step 2: Main Dashboard**

Display four large options: Add Sale, Add Expense, Customer Udhaar, and Daily Report, along with a prominent microphone button.

Dukaan Dost says: "Namaste! Aaj main aapki kya madad kar sakta hoon?"

**Step 3: Recording Transactions**

The shopkeeper presses the microphone and says: "Aaj Ramesh ko 500 rupaye ka udhaar diya."

Dukaan Dost responds: "Ramesh ko 500 rupaye ka udhaar record kar doon?"

Display the customer's name, amount, transaction type, and date. Save only after confirmation.

**Step 4: Adding Sales and Expenses**

User says: "Aaj 2000 rupaye ki sale hui."

Dukaan Dost responds: "Aaj ki sale 2000 rupaye record ho gayi."

User says: "500 rupaye ka saman kharida."

Dukaan Dost responds: "500 rupaye ka expense add kar diya gaya."

**Step 5: Checking Reports**

User asks: "Aaj kitni kamai hui?"

Dukaan Dost calculates recorded sales and expenses and responds: "Aaj ki total sale 2000 rupaye hai aur expenses 500 rupaye hain. Estimated balance 1500 rupaye hai."

**Step 6: Customer Payments**

User asks: "Kis customer ka udhaar baaki hai?"

Dukaan Dost reads out pending customer payments and displays them in a simple list.

## 3. Handling Real-World Problems

- **Background noise:** Use noise cancellation and ask users to repeat unclear sentences.
- **Different accents:** Support regional Indian accents without forcing standard pronunciation.
- **Mixed languages:** Understand Hinglish and regional language-English combinations naturally.
- **Misheard input:** Repeat important details such as customer names and amounts and ask for confirmation before saving.
- **Internet problems:** Save confirmed transactions locally and synchronize them when connectivity returns.
- **Silence:** Say, "I couldn't hear you. Please try again."

## 4. Prototype Requirements

Create a simple mobile interface with a large microphone button, multilingual voice interaction, transaction history, customer credit records, daily reports, and confirmation screens. Use sample business data to demonstrate the complete workflow. Display text alongside spoken responses so users can verify information.

The final prototype must demonstrate how an Indian shopkeeper can manage everyday business activities naturally by speaking instead of typing or navigating complicated accounting applications.

## 5. Real-Time Customer-Shopkeeper Language Translation

Add a multilingual voice translation feature that allows customers and shopkeepers who speak different Indian languages to communicate naturally.

**Step 1: Language Preferences**

During setup, ask the shopkeeper to select their preferred language. Allow customers to speak in any supported Indian language without requiring them to change their language.

**Step 2: Customer Speaks**

For example, a customer speaks in Telugu: "నాకు ఒక కిలో బియ్యం కావాలి."

**Step 3: Automatic Translation**

Dukaan Dost detects the customer's language, translates the sentence into the shopkeeper's preferred language (for example, Hindi), and reads it aloud: "मुझे एक किलो चावल चाहिए।"

Also display the translated text on the screen.

**Step 4: Shopkeeper Responds**

The shopkeeper replies in Hindi: "यह 60 रुपये का है।"

Dukaan Dost translates the response into Telugu and reads it aloud to the customer.

**Step 5: Continuous Conversation**

Keep both languages active during the conversation. Automatically detect the speaker's language, translate the message into the other person's preferred language, and play the translated audio. Provide a replay button and an option to correct or repeat unclear translations.

**Handling Translation Problems:**
- Support regional Indian accents and dialect variations.
- Understand mixed-language speech, such as Telugu-English and Hinglish.
- If speech is unclear, ask the speaker to repeat it instead of guessing.
- Display the original sentence and its translation together.
- Allow users to replay translated speech.
- Never silently change prices, quantities, product names, or important transaction details.
- Require confirmation before recording any financial transaction.

The goal is to make Dukaan Dost a multilingual bridge that removes language barriers between customers and shopkeepers across India.
