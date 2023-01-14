     }
            double sonuc;
            double sayi1 = Convert.ToInt32(textBox1.Text);
            double sayi2 = Convert.ToInt32(textBox2.Text);
            if (toplama.Checked)
                sonuc = sayi1 + sayi2;
            else if (çıkarma.Checked)
                sonuc = sayi1 - sayi2;
            else if (çarpma.Checked)
                sonuc = sayi1 * sayi2;
            else
                sonuc = sayi1 / sayi2;
            label1.Text = sonuc.ToString(); 
      }
