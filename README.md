# Team CH2-PS341
1. (MD) A281BSX2574 – Emeninta Angelina Natasya Pelawi 
2. (MD) A002BSY2176 – Muhammad Raihan Aulia
3. (CC) C010BSY3991 – Loanda Gunawan 
4. (CC) C002BSY3102 – Thirafi Najwan Kurniatama
5. (ML) M002BSX1738 – Cyntia Agnes Priscilla 
6. (ML) M324BSY0703 – Wilnanda Agung Putra
7. (ML) M010BSY0110 - Virdian Harun Prayoga

# Cloud Computing (Backend)
To start the backend services, one can do (assuming NodeJS 21 LTS is installed):
1. `cd capstone-bangkit-cc`
2. `npm i`
3. `npx prisma generate`
4. `npm run build`
5. `npm run start`

For populating the database, one can use
1. `ts-node src/crawler/crawl.ts`

# Machine Learning (Model)
How to do inferences with the models:
1. Access "Model Inference.ipynb" in Colab Files folder 
2. Run every cell available
3. To do subjectivity inference, use subj_predict method; for bias, use bias_predict; and neutrelity inference, use netr_predict.

# Mobile Development (Apps)
Android Application for Sinari

## Instruction to Build the Project
1. Clone the MD module repository
2. Open project using Android Studio
3. Wait for gradle build to finish
4. Connect an Android device to computer
5. Click the "Run" button and in the toolbar. Select the device. The app should be usable now.

## Technologies
1. Android Studio
2. Kotlin Coroutines
3. Retrofit
4. MPAndroidChart
5. Glide
6. OkHTTP

## Screenshots

<img src="https://img.thr.fi/content/IMG-20231222-WA0000-1703209714.jpg" width="300px" style="margin-right: 15px;" height="100%" />
<img src="https://img.thr.fi/content/app-1-1703209730.png" width="300px" height="100%" />
<br /><br />
<img src="https://img.thr.fi/content/app-2-1703209736.png" style="margin-right: 15px;" width="300px" height="100%" />
<img src="https://img.thr.fi/content/app-3-1703209744.png" width="300px" height="100%" />
<br /><br />
<img src="https://img.thr.fi/content/app-4-1703209759.png" style="margin-right: 15px;" width="300px" height="100%" />
<img src="https://img.thr.fi/content/app-5-1703209771.png" width="300px" height="100%" />
<br /><br />
<img src="https://img.thr.fi/content/app-6-1703209792.png" width="300px" height="100%" />