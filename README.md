# Old Church Slavonic Converter + Lemmatizer

## Overview

A tool for **converting** and **lemmatizing** Old Church Slavonic (OCS) text.

The project is available in two versions:

- **Desktop Application** — uses a dictionary-based word–lemma approach.
- **Web-Based Application** — uses the neural **OldSlavicLemma** Sequence-to-Sequence model.

Users can paste OCS text, generate converted and lemmatized output, and explore the results through an easy-to-use interface.

## Features

* **Text Conversion**  
  *Converts OCS text into the target/standardized form using built-in conversion rules and character mappings.*

* **Text Lemmatization**  
  *Provides dictionary-based lemmatization in the desktop application and neural character-level lemmatization in the web application.*

* **Word–Lemma Table**  
  *Displays word–lemma mappings in a clear tabular format in the application.*

* **Interactive Interface**  
  *Provides a simple interface for entering OCS text and viewing converted and lemmatized results.*


## Desktop Application
Download the Windows executable here:

https://drive.google.com/file/d/1A_L7D18CKcBn-yOEuyTMabwJ0gKpgeSY/view?usp=sharing

## Web-Based Application

The tool is also available as a web-based application and can be used directly in a browser.

The web application uses **OldSlavicLemma**, a dictionary-free neural **Sequence-to-Sequence (Seq2Seq)** model for Early Slavic lemmatization.

The model treats lemmatization as a **character-level sequence transduction task** and generates the lemma character by character from the input word while also using surrounding contextual information.

The model is designed to improve generalization to unseen word forms, orthographic variation, and ambiguous forms.

Use the web application here:

[[https://huggingface.co/spaces/usmannawaz/converter](https://huggingface.co/spaces/usmannawaz/ocscomtool)](https://huggingface.co/spaces/usmannawaz/ocscomtool)


## Model Retraining

The neural **OldSlavicLemma** model can be trained or retrained using annotated word–lemma data.

Training can be performed using newly annotated OCS data or by combining new OCS training data with existing OCS resources.

For model training, retraining, architecture, and evaluation code, see the corresponding **OldSlavicLemma source-code repository**.


https://github.com/usmannawaz01/OldSlavicLemma



