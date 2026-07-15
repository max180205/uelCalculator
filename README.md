public class FuelCalculator {
    public static void main(String[] args) {
        float FuekPrice = 245.5f;
        float liters = 47.5f;
        float totalsum = FuekPrice * liters;
        if (totalsum>10_000){
            totalsum= totalsum * 0.9f;
            System.out.println("10% жеңілдікпен шыкан сома_:"+totalsum);
        }
        else {
            System.out.println("Толенетын сома:"+totalsum);
        }
    }
}
