<div align="center">
  <h1>🏥 Medical AI Projects</h1>

</div>

<hr/>

<h2>📚 Notebooks inclus</h2>

<h3>🫁 1. Chest X-Ray Medical Diagnosis</h3>
<ul>
  <li><b>But :</b> Détection de pneumonie à partir d’images radiographiques pulmonaires.</li>
  <li><b>Technologies utilisées :</b>
    <ul>
      <li>CNN <code>DenseNet121</code> avec <b>Keras/TensorFlow</b> (Transfer Learning).</li>
      <li><code>ImageDataGenerator</code> pour l’augmentation et la normalisation des images.</li>
      <li><b>Grad-CAM</b> pour l’explicabilité du modèle.</li>
    </ul>
  </li>
  <li><b>Librairies principales :</b> tensorflow, keras, numpy, pandas, matplotlib, seaborn.</li>
</ul>

<h3>🧠 2. Alzheimer’s Disease Prediction</h3>
<ul>
  <li><b>But :</b> Prédire les stades ou le risque d’Alzheimer à partir de données médicales et d’images.</li>
  <li><b>Technologies utilisées :</b>
    <ul>
      <li>Transfer Learning avec <code>DenseNet169</code>.</li>
      <li>Prétraitement avec <b>scikit-image</b> (conversion, redimensionnement, RGB).</li>
      <li>Régularisation avec Dropout, callbacks <code>EarlyStopping</code> &amp; <code>ModelCheckpoint</code>.</li>
    </ul>
  </li>
  <li><b>Résultat :</b> Score AUC ≈ <b>0.90</b>.</li>
  <li><b>Librairies principales :</b> tensorflow, keras, scikit-image, pandas, matplotlib, tqdm.</li>
</ul>

<h3>💉 3. Diabetes Prediction (ML)</h3>
<ul>
  <li><b>But :</b> Prédire la probabilité qu’un patient soit diabétique à partir de variables cliniques.</li>
  <li><b>Technologies utilisées :</b>
    <ul>
      <li>Modèles ML classiques : Logistic Regression, SVM, Decision Tree, Random Forest, Naive Bayes, KNN.</li>
      <li>Réseau de neurones simple (Keras Sequential) comme baseline deep learning.</li>
      <li>Normalisation avec <code>StandardScaler</code> et analyse de corrélations.</li>
    </ul>
  </li>
  <li><b>Librairies principales :</b> scikit-learn, tensorflow.keras, numpy, pandas, matplotlib, seaborn.</li>
</ul>
<h3>❤️ 4. Heart Disease Prediction</h3>
<ul>
  <li><b>But :</b> Prédire la présence ou non de maladies cardiaques à partir de variables cliniques (âge, tension, cholestérol, douleurs thoraciques, etc.).</li>
  <li><b>Technologies utilisées :</b>
    <ul>
      <li>Classificateurs testés : Logistic Regression, Naive Bayes, SVM, Random Forest, KNN, XGBoost.</li>
      <li>Prétraitement : normalisation avec <code>StandardScaler</code>, analyse exploratoire des données.</li>
      <li>Évaluation via matrices de confusion, accuracy et classification reports.</li>
      <li><b>Meilleur modèle :</b> SVM sur le dataset testé.</li>
    </ul>
  </li>
  <li><b>Librairies principales :</b> scikit-learn, xgboost, numpy, pandas, matplotlib, seaborn.</li>
</ul>

<hr/>


