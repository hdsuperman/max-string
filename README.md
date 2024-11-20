# max-string

`max-string` is a lightweight utility library that provides predefined maximum lengths for common
data types and formats. This package simplifies your workflow for database schema validation,
frontend form validation, and backend API validation. The values are derived from widely recognized
international standards, ensuring accuracy and reliability.

## 📦 Installation

Install the package:

```shell
npm install max-string
yarn add max-string
pnpm add max-string
```

## 🌐 Use Cases

1. Frontend Form Validation: Add constraints to input fields based on predefined maximum lengths.
2. Backend API Validation: Validate incoming data payloads to meet expected length requirements.
   3Database Schema Validation: Ensure your string column lengths are properly defined to avoid
   truncation.

## 📘 Usage

```typescript
import { MAX_STRING } from 'max-string';

console.log(MAX_STRING.PHONE_NUMBER); // 15
```
