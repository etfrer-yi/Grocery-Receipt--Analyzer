# Grocery-Receipt--Analyzer

Goal: Be able to process grocery store receipts so that...
Input: Grocery store receipt image (PNG, JPG, or similar format)
Output: Some kind of format (PDF or otherwise) that contains information about the foods bought, their prices, and some extra information

Steps:
0. Frontend with drag-and-drop for dropping/selecting image into it.
1. Basic backend able to service the website and receive requests of images sent to it.
2. Given the received image in backend, perform OCR. Detect for (item, price) tuples and other info. 
3. Send it to the front-end as JSON (easy).
4. Generate an editable form given the (item, price) tuples and other info.
5. Generate PDF or other output format based off the editable form submitted. This could involve frontend and backend work.

Tech stack:
- React.js for frontend with Chakra UI or Material UI
- FastAPI (Python) for backend
- pytesseract or Keras-OCR (Python) for OCR
- 
