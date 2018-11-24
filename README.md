# tecacsEncapsulation

class test {
    private String sName;
    private int sId;
    
    public String getsName() {
        return sName;
    }

    public void setsName(String sName) {
        this.sName = sName;
    }

    public int getsId() {
        return sId;
    }

    public void setsId(int sId) {
        this.sId = sId;
    }
}
    public class student {
        public static void main(String[] args) {
            test obj = new test();
            obj.setsName("Value 1");
            obj.setsId(45);
            System.out.println("Studemt name: " + obj.getsName());
            System.out.println("Studemt ID: " + obj.getsId());
        }
    }
