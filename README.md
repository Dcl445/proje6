# proje6

 Scanner klv = new Scanner(System.in);
        System.out.println("armut kg giriniz");
        double armut = klv.nextDouble();
        System.out.println("elma kg giriniz");
        double elma = klv.nextDouble();
        System.out.println("domates kg giriniz");
        double domates = klv.nextDouble();
        System.out.println("muz kg giriniz");
        double muz = klv.nextDouble();
        System.out.println("patlıcan kg giriniz");
        double patlican = klv.nextDouble();

        double armuta = 2.14;
        double elmab = 3.67;
        double domatesc = 1.11;
        double muzd = 0.95;
        double patlicane = 5;
        armut = armut * 2.14;
        elma = elma * 3.67;
        domates = domates * 1.11;
        muz = muz * 0.95;
        patlican = patlican * 5;
        double toplam = armut + elma + domates + muz + patlican;
        System.out.println("\n armut" + armut + "\n elma" + elma + "\n domates" + domates + "\n muz" + muz + "\npatlican" + patlican);
        System.out.println("toplam kg=" + toplam);
