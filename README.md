# UAS Fisika Komputasi Kelas 01
Ujian 2 Fisika Komputasi ITB dengan anggota kelompok :
- 

## No.1
### a.

    Pada sistem bandul berlaku hukum-hukum newton yang diantaranya adalah,
    1. Pada keadaan setimbang
    \begin{equation}
    \label{eqn:newt1}
    \sum{F} = 0
    \end{equation}

    Menggunakan persamaan \eqref{eqn:newt1} maka pada saat kondisi sebelum dilepas gaya yang bekerja pada bandul mengikuti Hukum 1           Newton dengan,

    \begin{equation}
    \label{sentri}
    T = mg\cos {\theta} - \frac{mv^2}{l} = mg\frac {y}{l} - \frac{mv^2}{l}
    \end{equation}

    Dengan $\theta$ merupakan sudut antara $l$ dan $y$
    
    2. Pada keadaan bandul bergerak
    Akan mengikuti hukum kedua Newton
    \begin{equation}
    \label{eqn:newt2}
    \sum{F} = ma
    \end{equation}
    
    Maka dilakukan analisis dengan dekomposisi sumbu x dan y. Untuk sumbu x didapat resultan gaya yaitu
    \begin{equation}
    \label{eqn:fx}
    \sum{F_x} = -F_{gesek angin (arah x)}-T\sin{\theta} = -(3 \pi \eta D)\dot{x} - (mg\frac {y}{l} - \frac{mv^2}{l})\frac{x}{l} =m\ddot{x}
    \end{equation}
    Sehingga didapat persamaan gerak x adalah
    \begin{equation}
    \label{eqn:dodox}
    \ddot{x} + \left( \frac{3 \pi \eta D}{m} \right) \dot{x} - \left( \frac{1}{l^2} \right) (\dot{x}^2 + \dot{y}^2) x + \left( \frac{g}{l^2} \right) xy = 0
    \end{equation}
    
    Untuk sumbu y didapat resultan gaya yaitu
    \begin{equation}
    \label{eqn:fy}
    \sum{F_y} = -F_{gesek angin (arah y)}+T\cos{\theta}-mg = -(3 \pi \eta D)\dot{y} + (mg\frac {y}{l} - \frac{mv^2}{l})\frac{y}{l} - mg =m\ddot{y}
    \end{equation}
    Sehingga didapat persamaan gerak y adalah
    \begin{equation}
    \label{eqn:dodoy}
    \ddot{y} + \left( \frac{3 \pi \eta D}{m} \right) \dot{y} + \left( \frac{1}{l^2} \right) (\dot{x}^2 + \dot{y}^2) y - \left( \frac{g}{l^2} \right) y^2 = -g.
    \end{equation}
    
### b.

    Makna dari masing-masing suku pada persamaan gerak adalah
    
    1. Suku pertama menunjukan percepatan pendulum
    2. Suku kedua menunjukann gaya gesek udara dengan menggunakan Hukum Stokes dan gaya gesek ini sebanding dengan kecepatan yang berlawanan arah dengan gaya gesek.
    3. Suku ketiga dan keempat merupakan gaya dari tegangan tali yang merupakan coupling dari gaya sentripetal dan gaya berat yang bekerja pada tali
    4. Dan suku kelima diruas kanan merupakan gaya eksternal yang bekerja pada sistem
    
    Semua suku dinyatakan dalam satuan per massa
    
### c.

    Ketika tidak ada gesekan udara maka fluida yang dilewati merupakan fluida yang inviscid artinya viskositas $\eta$ = 0.
    Sehingga persamaan \eqref{dodox} dan \eqref{dodoy} dapat ditulis sebagai,
    
    \begin{equation}
    \label{dodox2}
    \ddot{x} - \left( \frac{1}{l^2} \right) (\dot{x}^2 + \dot{y}^2) x + \left( \frac{g}{l^2} \right) xy = 0
    \end{equation}
    
    dan
    
    \begin{equation}
    \label{dodoy2}
    \ddot{y} + \left( \frac{1}{l^2} \right) (\dot{x}^2 + \dot{y}^2) y - \left( \frac{g}{l^2} \right) y^2 = -g.
    \end{equation}
    
### d.

    Untuk bandul dengan simpangan kecil dan tanpa gesekan maka didapatkan bahwa
    
    \begin{equation}
    \cos{\theta}=\frac{y}{1}=1
    \end{equation}
    
    dan
    
    \begin{equation}
    \sin{\theta}=\frac{x}{1}=\theta
    \end{equation}
    
    Sehingga persamaan \eqref{dodox} dan \eqref{dodoy} dapat ditulis sebagai,
    
    \begin{equation}
    \label{dodox3}
    \ddot{x} - \left( \frac{\theta}{l} \right) (\dot{x}^2 + \dot{y}^2) x + g \theta= 0
    \end{equation}
    
    \begin{equation}
    \label{dodoy3}
    \ddot{y} - \left( \frac{1}{l} \right) (\dot{x}^2 + \dot{y}^2) y = 0
    \end{equation}
    
## No.2
    





