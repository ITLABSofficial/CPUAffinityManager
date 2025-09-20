# CPUAffinityManager

## Türkçe

Merhaba! 👋  

Bu program, **Windows üzerinde çalışan uygulamaların hangi CPU çekirdeklerini kullanacağını** seçmenizi sağlayan basit ama güçlü bir araçtır. Yani artık bir işlemin sadece belirli çekirdeklerde çalışmasını sağlayabilir, performansı biraz daha kontrol edebilirsiniz.

### Neler yapabilirsiniz?
- Bilgisayarınızda çalışan tüm uygulamaları listeleyebilirsiniz.
- Çift tıkladığınız bir işlem için çekirdek seçimi yapabilirsiniz.
- Seçtiğiniz çekirdeklerde işlemi çalıştırabilirsiniz.
- İsterseniz seçilen işlemin affinitisini **tüm çekirdekleri kullanacak şekilde sıfırlayabilirsiniz**.
- Tek tıkla GitHub sayfasına gidebilirsiniz (projeyi görmek veya katkıda bulunmak için).

### Gereksinimler
- Windows işletim sistemi (PowerShell yüklü olmalı)
- Java 11 veya üstü
- Yönetici hakları bazı işlemler için gerekli olabilir.

### Nasıl kullanılır?
1. Programı başlatın.
2. **Tara** butonuna basarak çalışan uygulamaları listeleyin.
3. Listeden bir işlem seçin ve **çift tıklayın**.
4. Açılan pencereden hangi çekirdekleri kullanacağını seçin ve **OK** deyin.
5. İşlem seçtiğiniz çekirdeklerde çalışmaya başlayacaktır.
6. Affinity’yi eski haline getirmek veya tüm çekirdekleri kullanmak için **Dur** butonuna basabilirsiniz.

> Not: Eğer çekirdek atama işlemi başarısız olursa, programı **yönetici olarak çalıştırmayı deneyin**.

### GitHub
Projeyi görmek veya katkıda bulunmak için: [https://github.com/ITLABSofficial](https://github.com/ITLABSofficial)

---

## English

Hello! 👋  

This program is a simple but powerful tool that lets you **choose which CPU cores a Windows application should run on**. You can now make a process run only on certain cores and have a bit more control over performance.

### What can you do?
- List all running applications on your PC.
- Double-click a process to choose which CPU cores it should use.
- Apply the selected CPU cores for that process.
- Reset the process affinity to use **all cores** if you want.
- Quickly go to the GitHub page (to see the project or contribute).

### Requirements
- Windows OS (PowerShell must be installed)
- Java 11 or higher
- Admin rights might be required for some processes.

### How to use?
1. Launch the program.
2. Click **Tara (Scan)** to list running applications.
3. Select a process and **double-click** it.
4. Choose which cores it should run on in the dialog and press **OK**.
5. The process will start running on the selected cores.
6. To reset affinity or use all cores, click **Dur (Stop)**.

> Note: If setting the affinity fails, try **running the program as Administrator**.

### GitHub
Check out the project or contribute here: [https://github.com/ITLABSofficial](https://github.com/ITLABSofficial)
