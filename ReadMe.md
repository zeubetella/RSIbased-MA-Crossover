# RSIbased-WMA-Crossover / Türkçe Açıklama / Please scroll down for English description

Bu indikatör, belirli koşullar altında al ve sat sinyalleri üretmek amacıyla RSI (Göreceli Güç Endeksi) ve RSI bazlı iki hareketli ortalama (MA) kullanarak bir grafik oluşturur.

İndikatör, pinescriptv5 üzerine yazılmıştır. Kullanıcı, RSI uzunluğunu ve kaynak değişkenini ayarlamak için input değişkenlerini kullanabilir.

Daha sonra, iki hareketli ortalama için hesaplamalar yapılır. Kullanıcı, MA türünü (WMA, EMA, SMA, VWMA) ve uzunluğunu ayarlamak için input değişkenlerini kullanabilir.

Hesaplamalar kullanılarak RSI + MA, plot fonksiyonu ile üç çizgi olarak grafikte çizdirilir. Ayrıca, fill fonksiyonu kullanılarak RSI grafiği üzerinde oversold-rsi65-midline-rsi35-overbought bölgeleri gösterilir.

Kesişimler, ta.crossover ve ta.crossunder fonksiyonları kullanılarak tespit edilir ve plotshape fonksiyonu kullanılarak grafikte uygun şekillerle gösterilir.

İndikatör 1 saat ve altındaki periyotlarda daha iyi çalışmaktadır.

Umarım bu açıklama kodu daha iyi anlamanıza yardımcı olur.

Yatırımlarınızda sadece bu indikatörü kullanmanız riskli olabilir, lütfen bu sorumluluğun farkında olun.

# RSIbased-WMA-Crossover / English description

This indicator creates a chart using the Relative Strength Index (RSI) and RSI-based two moving averages (MA) to generate buy and sell signals under certain conditions.

The indicator is written on pinescriptv5. Users can adjust the RSI length and source variable by using input variables.

Calculations are then made for two moving averages. Users can adjust the MA type (WMA, EMA, SMA, VWMA) and length using input variables.

Using the calculations, RSI + MA is plotted on the chart with three lines using the plot function. Additionally, the fill function is used to display oversold-rsi65-midline-rsi35-overbought regions on the RSI chart.

Crossovers are detected using the ta.crossover and ta.crossunder functions and displayed on the chart using the plotshape function.

The indicator works better on timeframes of 1 hour and lower.

Please note that using only this indicator for your investments may be risky. Please be aware of this responsibility.
