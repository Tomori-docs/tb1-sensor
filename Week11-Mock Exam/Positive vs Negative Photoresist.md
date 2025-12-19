Figure Q6 illustrates the photolithography steps for patterning the photoresist
layer. Identify the incorrect statement: (2 marks)
![](/file/2/Dmf1GDlwvIOAjUF_W1ICA.png "Figure Q6. Photolithography steps.")
A. Baking is usually required after the second step.
B. A negative photoresist is used in this process.
C. Developing the photoresist in the last step enables transferring the pattern of
the mask to the photoresist.
D. None of the above statements is incorrect.


答案：B

解析：
好的，这是对光刻工艺步骤图示的分析和答案解析。

## 🔬 光刻工艺步骤分析及答案解析

您提供的图片 **Figure Q6** 展示了光刻（Photolithography）工艺的基本步骤，用于在硅片（Silicon）上方的光刻胶（Photoresist）层上形成图案。

**Figure Q6 所示的步骤流程：**

1.  **涂胶 (Coating):** 硅片上覆盖一层光刻胶。
2.  **曝光 (Exposure):** 通过一个带有图案的光掩模（Photomask），用紫外光（UV light）照射涂有光刻胶的硅片。
3.  **显影 (Developing):** 经过曝光后，去除光刻胶的特定区域，在光刻胶层上形成图案。

---

### **选项分析 (中文)**

#### **A. 曝光后的烘烤 (Post-exposure Baking)**

> *A. Baking is usually required after the second step.*
> *A. 第二步之后通常需要烘烤。*

* **分析：** 第二步是紫外光曝光。在曝光之后、显影之前，通常会进行一个被称为 **曝光后烘烤 (Post-Exposure Bake, PEB)** 的步骤。
* **作用：** PEB 的主要目的是减少驻波效应（standing wave effects）和改善图形侧壁的陡直度。对于化学放大光刻胶 (Chemically Amplified Resist, CAR)，PEB 还是驱动曝光区域化学反应的关键步骤。
* **结论：** 语句 **A 是正确的**。

#### **B. 光刻胶的类型 (Photoresist Type)**

> *B. A negative photoresist is used in this process.*
> *B. 此过程中使用了负性光刻胶。*

* **分析：**
    * **负性光刻胶 (Negative Photoresist):** 在紫外光**照射到的区域**，光刻胶会发生交联反应，变得**不溶于显影液**而被保留下来。
    * **正性光刻胶 (Positive Photoresist):** 在紫外光**照射到的区域**，光刻胶会发生降解反应，**溶于显影液**而被去除。
* **图示判断：** 在 Figure Q6 中，光掩模被设计成只让光线透过**图案边缘**。曝光后，**光线照射到的区域**（掩模下方未被遮挡的部分）在显影后**被去除了**，而未被照射的区域（掩模下方被遮挡的部分）则被保留下来。
* **结论：** 这种“见光就去除”的特性是**正性光刻胶**的特点。因此，语句 **B 是错误的**。

#### **C. 显影的作用 (Developing)**

> *C. Developing the photoresist in the last step enables transferring the pattern of the mask to the photoresist.*
> *C. 最后一步显影光刻胶可以将掩模的图案转移到光刻胶上。*

* **分析：** 显影是光刻工艺的最终步骤，它利用显影液溶解并去除光刻胶的特定区域（正胶是曝光区，负胶是未曝光区）。这个过程的结果就是在光刻胶层上**精确地再现（转移）**了光掩模上的图案。
* **结论：** 语句 **C 是正确的**。

#### **D. 总结 (Conclusion)**

> *D. None of the above statements is incorrect.*
> *D. 以上说法均不正确。*

* **分析：** 由于语句 B 是错误的，因此 D 选项不成立。

---

### **最终答案**

根据上述分析，**错误**的陈述是 **B**。

**答案：B**

---


知识点：
• How the photolithography can be used to
pattern micron-scale features?
• What is the difference between positive and
negative photoresist?
![](/file/2/c9Ik9Jt1KozzlWuASKk5o.png)

回答：
这幅图清晰地展示了**光刻技术 (Photolithography)** 的关键步骤，以及**正性光刻胶 (Positive Resist)** 和**负性光刻胶 (Negative Resist)** 之间的核心区别。

以下是关于您知识点的详细解释：

---

## 🔬 光刻如何实现微米级图案化？ (How Photolithography is used to pattern micron-scale features?)

光刻技术是一种在半导体制造（如芯片）和微机电系统（MEMS）中，用于将**掩模 (Mask)** 上的几何图形转移到**晶圆 (Wafer)** 表面，从而实现**微米甚至纳米级**精细图案化的核心工艺。其图案化流程类似于传统摄影：

1.  **涂胶 (Coating)**: 在硅 (Si) 或其他衬底上旋涂一层**光刻胶 (Photoresist, PR)**，这是一种对紫外线 (UV) 敏感的聚合物薄膜 (图A $\rightarrow$ 图B)。
2.  **曝光 (Exposure)**: 将带有预定图案的**掩模**放置在光刻胶上方，然后用紫外光照射 (图C)。掩模上的不透明区域会阻挡光线，透明区域则允许光线通过。
    * **关键**: 光源的波长 ($\lambda$) 和光学系统的数值孔径 ($\text{NA}$) 决定了光刻能达到的**分辨率 (Resolution)**，即能制造的最细小特征尺寸。通过使用更短波长的光（如深紫外光 $\text{DUV}$）和高 $\text{NA}$ 的光学系统，可以将图案尺寸缩小到微米以下。
3.  **显影 (Development)**: 经过曝光的光刻胶，其化学性质会发生改变（取决于光刻胶类型）。然后使用特定的**显影液**选择性地去除部分光刻胶，将掩模上的图案**转移**到光刻胶层上 (图D)。
4.  **刻蚀 (Etching)**: 以图案化的光刻胶层为**掩膜**，对下方裸露的衬底或薄膜进行刻蚀（如干法刻蚀或湿法刻蚀）。光刻胶保护了未暴露区域，刻蚀剂只去除未受保护的区域 (图E $\rightarrow$ 图F)。
5.  **去胶 (Stripping)**: 最后，去除剩余的光刻胶，完成衬底或薄膜层的图案化。

通过精确控制这些步骤，光刻技术能够将复杂的电路或微结构图案高保真地复制到晶圆上，实现**微米级 (micron-scale)** 甚至更小特征的制造。

---

## 💡 正性光刻胶与负性光刻胶的区别 (Difference between Positive and Negative Photoresist)

正性光刻胶和负性光刻胶的主要区别在于它们**对曝光的反应**以及**显影后形成的图案**：

| 特性 | 正性光刻胶 (Positive Resist) | 负性光刻胶 (Negative Resist) |
| :--- | :--- | :--- |
| **曝光反应** | 曝光区域的聚合物**分解**或**变得易溶**于显影液。 | 曝光区域的聚合物发生**交联 (Cross-linking)** 或**聚合**，**变得不溶**于显影液。 |
| **显影结果** | 显影液**溶解并移除**被光照到的区域。 | 显影液**溶解并移除**未被光照的区域。 |
| **最终图案** | 形成与**掩模图案相同**的图形（正像）。 | 形成与**掩模图案相反**的图形（负像）。 |
| **图示参照** | 参照左侧流程：**C** $\rightarrow$ **D** 曝光区域被移除，**F** 图案与掩模相同。 | 参照右侧流程：**C** $\rightarrow$ **D** 未曝光区域被移除，**F** 图案与掩模相反。 |
| **分辨率** | 通常具有**更高**的分辨率（可用于更精细的图案）。 | 分辨率通常**较低**，因为交联会导致边缘轻微膨胀。 |
| **应用倾向**| 常用于对精度要求高的**先进半导体**制造。 | 常用于对机械强度或厚膜要求较高的**微系统**制造。 |

**总结：**

* **正性光刻胶**：见光**溶解**，留下的图案**与光罩相同**。
* **负性光刻胶**：见光**固化**，留下的图案**与光罩相反**。



来源：
![](/d/Jacka1_/file/2/rZ1XFiPmFxkG7EQ5BofOr.png "Photography")
![](/d/Jacka1_/file/2/D9KY_Bl4sinvbnTY_n8sa.png "Film development")
![](/d/Jacka1_/file/2/jQI3iBDwdR5eDQUkJBZXj.png "Photolithography")


---

## 📸 Photolithography

* **Patterning micro/nano-structures on a substrate.** E.g., micro-scale patterns of a photoresist on a Si wafer. Usually, the patterned photoresist layer is used for patterning of another layer (e.g., $\text{SiO}_2$) underneath through etching.
* The process begins with producing a **mask** (i.e., a chromium pattern on a glass plate). The wafer is then coated with a polymer (**photoresist**) which is sensitive to ultraviolet light. Ultraviolet light is then shone through the mask onto the photoresist. The photoresist is then developed which transfers the pattern on the mask to the photoresist layer.
* There are two types of photoresist, **positive** and **negative**.
    * Where the ultraviolet light strikes the **positive resist** it weakens the polymer, so that when the image is developed the resist is washed away where the light struck it.
    * The opposite occurs with the **negative resist**.
* A chemical (or some other method) is then used to remove $\text{SiO}_2$ where it is exposed through the openings in the resist. Finally, the resist is removed by using a solution leaving the patterned $\text{SiO}_2$.

![](/file/2/hV2SR0puEq4DaZQ3SdGUP.png "Fig 16. Positive and
negative photolithography.")
