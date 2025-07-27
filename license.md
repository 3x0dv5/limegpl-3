# LimeGPL License Version 3 (LimeGPL-3.0)
_Adapted from the GNU General Public License version 3 (GPL-3.0)_

Copyright (C) 2025 Rui Lima, https://github.com/3x0dv5/limegpl-3

Everyone is permitted to copy and distribute verbatim copies of this license document, but modifying it is not allowed.

---

## Preamble

The LimeGPL-3 license is a strong copyleft license that ensures software freedom while restricting the use of the licensed code in the context of training artificial intelligence (AI) models.

This license preserves the freedoms to use, study, modify, and redistribute software, but it requires that any AI model trained using the software must be open-weight or fully open source, in accordance with the definitions set out below. This ensures that the fruits of community contributions remain accessible to the broader public and are not enclosed within proprietary AI systems.

This license is not approved by the Free Software Foundation or the Open Source Initiative. It is an independent derivative of the GNU GPL-3 and should not be referred to as "GPL" without the "Lime" prefix.

---

## Definitions

### “Open-Weight AI Model”

An **Open-Weight AI Model** is defined as a machine learning model whose:
- Trained weights,
- Model architecture and configuration,
- Inference code,

are publicly released in a form that allows individuals to **download and run the model**, **without requiring paid APIs or proprietary infrastructure**.

There is no restriction on the type of hardware used to execute such models.

### “Fully Open Source AI Model”

A **Fully Open Source AI Model** meets all criteria of an Open-Weight AI Model, and in addition:
- Releases full training code,
- Provides the datasets used or instructions to obtain or recreate them,
- Shares all preprocessing steps, hyperparameters, and fine-tuning configurations,

Such that the model’s training process is **fully reproducible** by independent researchers or developers.

---

## Terms and Conditions

This license incorporates all terms of the GNU General Public License version 3 (GPL-3.0), except where explicitly overridden below:

### 1. Additional Condition: AI Usage Restriction

The Licensed Material, or any derivative thereof, **must not** be used to train, fine-tune, distill, or otherwise develop **any AI model** unless that model qualifies as either:
- an **Open-Weight AI Model**, or
- a **Fully Open Source AI Model**.

This restriction applies regardless of whether the resulting model is intended for public use or internal deployment.

Any attempt to use the software in violation of this clause constitutes an immediate termination of your rights under this license.

---

### 2. Fair Use Exception for Non-Commercial Research

You may use the Licensed Material for **non-commercial**, **private**, or **academic research purposes**, including training or fine-tuning models whose weights are not initially released, provided that:
- The model is not used in production, monetized, or integrated into commercial products or services;
- The resulting weights are either:
  - Released at a later stage under an approved license, or
  - Retained for purely academic purposes such as peer-reviewed publication, thesis work, or reproducibility research.

---

## Compatibility

This license is **not compatible** with the standard GNU GPL-3 for purposes of code combination. It is a distinct license and must be treated as such.

---

## Disclaimer of Warranty

As with the GNU GPL, there is **no warranty** for the program, to the extent permitted by applicable law. Unless otherwise stated in writing, the copyright holders provide the program "as is" without warranty of any kind.

---

## Limitation of Liability

In no event will the licensors be liable for any damages arising from the use of the software, to the extent permitted by applicable law.

---

## Final Notes

The LimeGPL-3 license is intended for projects that want to ensure their code is not used to train proprietary AI models. It protects user freedom and transparency in the AI domain, while still supporting academic and personal experimentation.
