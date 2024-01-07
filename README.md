class Main
{
    int a=10;
    static int b=20;
    public static void main(String[] args)
    {
        Main s1=new Main();
        Main s2=new Main();
        System.out.println(s1.a+" "+s1.b);
        System.out.println(s2.a+" "+s2.b);
        s1.a=888;
        s2.a=999;
       System.out.println(s1.a+" "+s1.b);
       System.out.println(s2.a+" "+s2.b);
    }
}
