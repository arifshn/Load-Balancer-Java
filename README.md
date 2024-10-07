# Gelişmiş Load Balancer Projesi

Bu projede , Load Balancer sistemini daha gelişmiş bir şekilde Java ve Kafka kullanarak geliştirdim. Uygulama, yükü dağıtarak sürekli ve sorunsuz bir şekilde çalışmayı hedefliyor.

## Proje Hakkında

Bu projede, yük dengeleme işlevini yerine getiren bir Java uygulaması geliştirdim. Kafka ile entegre çalışarak veri üretimi ve tüketimi gerçekleştirdim.

## Adımlar

1. **Proje Dizini Oluşturma**:
   Projemin dosya dizinini oluşturup gerekli klasörleri ayarladım.

2. **Producer ve Consumer Dosyalarını Doldurma**:
   Kafka ile iletişim kurmak için producer ve consumer dosyalarının içini doldurdum.

3. **Docker ile İmaj Oluşturma**:
   Uygulamayı Docker ile imaj haline getirdim. `Dockerfile` ve `docker-compose.yml` dosyalarını oluşturarak gerekli yapılandırmaları yaptım.

4. **Konteyner Oluşturma ve Çalıştırma**:
   Oluşturduğum Docker imajını kullanarak bir konteyner oluşturdum ve çalıştırdım.

5. **Docker Hub ile Entegrasyon**:
   Docker Hub ile entegre bir şekilde çalışarak uygulamanın sorunsuz bir şekilde çalıştığını doğruladım.

6. **Kubernetes ile Dağıtım**:
   Projeyi Kubernetes üzerinde çalıştırdım. Kubernetes ile yük dengeleme işlevini test ettim.

## Sonuç

Bu projede, Load Balancer sistemini geliştirerek yükü dağıtma ve sürekli çalışabilirliği sağlama amacına ulaştım. Kafka ve Java kullanarak, veri akışını etkin bir şekilde yönlendirebildim. Docker ve Kubernetes ile uygulamanın taşınabilirliğini artırdım.
