![Dialy](https://i.imgur.com/7ErzpV2.png)

### **Turn Phone Numbers into Two Memorable Words**  

---

## **What is Dialy?**  
Dialy offers a fresh approach to phone numbers. Instead of memorizing random 10-digit sequences, Dialy assigns **two short, easy-to-remember words** to each phone number. Now, remembering a phone number is as simple as recalling two words!  

---

## **Why Does Dialy Exist?**  
Dialy was inspired by [What3Words](https://what3words.com/). Its creators explored new ways to make information easier to remember, and phone numbers quickly stood out as a prime candidate. They’re often hard to recall, but replacing them with two unique words simplifies the process dramatically.  

---

## **How Do I Use It?**  
Dialy was designed to be **simple and intuitive**.  

### **Step 1:** Enter a Number or Dialy  
- On the homepage, you’ll find a search bar:  
  ![Dialy Home Page](https://i.imgur.com/oQAb2J8.png)  

- Enter either:  
  - A **Dialy** (two words separated by a colon), or  
  - A **phone number**.  

- Dialy uses **Firebase-powered autocomplete** to ensure fast results.  
  ![Dialy autocomplete](https://i.imgur.com/dXEvCBE.png)  

### **Step 2:** View Results  
- If a **Dialy** is entered, you’ll see:  
  - The **original phone number** assigned to it.  
  - **Metadata** and **search history** associated with that number.  
  ![Dialy results](https://i.imgur.com/vr7yUgH.png)  

- If a **phone number** is entered, you’ll see:  
  - The **Dialy** assigned to it.  
  ![Dialy phone results](https://i.imgur.com/5DNUZrh.png)  

---

## **How Does It Work?**  
Dialy splits phone numbers into two groups of **5 digits**. Each group maps to one word, requiring **100,000 words** to cover all possibilities.  

### **Current Limitations**  
- Dialy currently supports **North American phone numbers only**.  
- Supporting international numbers would require significant changes to the codebase.  

### **Tech Stack**  
- **Frontend:** Vanilla JavaScript + Bootstrap  
- **Backend:** Firebase for:  
  - Data storage (phone-to-word assignments and search history)  
  - Hosting (free and fast!)  
- **API:** [Dialy API](http://api.dialy.xyz/)  
  - Repository: [GitHub](https://github.com/cra1gg/dialy-api)  
  - Uses Google’s [libphonenumber](https://github.com/google/libphonenumber) via a [Python wrapper](https://github.com/daviddrysdale/python-phonenumbers).  

---

## **About the Project**  
Dialy was developed for fun in **Summer 2020** by Cra1gg & shmkane. Bugs are possible—please report any issues you find!  
