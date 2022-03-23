# Convert-data-of-type-LONG-to-DateTime
Convert data of type LONG to DateTime
 public static String convertLongToDay(long timeStamp) {
        DateFormat dateFormat = new SimpleDateFormat("dd/MM/yyyy HH:mm:ss");
        Date date = new Date(timeStamp);
        return  dateFormat.format(date);
    }
