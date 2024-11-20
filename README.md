# max-length

`max-length` is a lightweight utility library that provides predefined maximum lengths for common
data types and formats. This package simplifies your workflow for database schema validation,
frontend form validation, and backend API validation. The values are derived from widely recognized
international standards, ensuring accuracy and reliability.

## 📦 Installation

Install the package:

```shell
npm install max-length
yarn add max-length
pnpm add max-length
```

## 🌐 Use Cases

1. Frontend Form Validation: Add constraints to input fields based on predefined maximum lengths.
2. Backend API Validation: Validate incoming data payloads to meet expected length requirements.
   3Database Schema Validation: Ensure your string column lengths are properly defined to avoid
   truncation.

## 📘 Usage

```typescript
import { MAX_LENGTH } from 'max-length';

console.log(MAX_LENGTH.PHONE_NUMBER); // 15
```
