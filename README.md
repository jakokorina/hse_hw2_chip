# hse_hw2_chip

Для работы была выбрана клеточная линия - GM23248 и гистоновая метка - H3K9ac:

## Обязательная часть

Сначала сделаем fastqc для 2х реплик + контроль:

`ENCFF270JKL.fastq`

В принципе, можно было не делать подрезание чтений, но мне не жалко пространства на гугл диске, вычислительных ресурсов гугл колаба и своего времени, все ради науки.

До:
<p float="left">
  <img src="/picture/stat_270_seq.png " width="400" />
  <img src="/picture/quality_270_seq.png" width="400" />
</p>

После:

<p float="left">
  <img src="/picture/stat_270_trim.png " width="400" />
  <img src="/picture/quality_270_trim.png" width="400" />
</p>

`ENCFF925DDM.fastq`

А в этом случае делать надо было, вот результат.
До:
<p float="left">
  <img src="/picture/stat_925_seq.png " width="400" />
  <img src="/picture/quality_925_seq.png" width="400" />
</p>

После:

<p float="left">
  <img src="/picture/stat_925_trim.png " width="400" />
  <img src="/picture/quality_925_trim.png" width="400" />
</p>

`control`

Здесь тоже сдало лучше, нужно было делать.

До:
<p float="left">
  <img src="/picture/stat_control.png " width="400" />
  <img src="/picture/quality_control.png" width="400" />
</p>

После:

<p float="left">
  <img src="/picture/stat_control_trim.png " width="400" />
  <img src="/picture/quality_control_trim.png" width="400" />
</p>
